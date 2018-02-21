---
layout: post
title:      "The tiniest mistake."
date:       2018-02-21 16:20:17 +0000
permalink:  the_tiniest_mistake
---


I just spent three days banging my head against the computer, thinking the last 9 months of studying have all been for nothing. I just didn't get it. At all. I googled every previous answer I could find. I studied each, hoping for some clue, but just could not figure out why doing it that way would help out with the error I was getting. It was the cash register OO lab, and the mistake was =+ vs. +=. Thank goodness for the "Ask a Question".

My code looked like this:

```
  class CashRegister
  
  attr_accessor :total, :discount

  def initialize (discount = 0)
    @total = 0
    @discount = discount
  end

  def add_item (title, price, quantity=1)
     self.total =+ price * quantity
  end
```

My error message looked like this:
```
1) CashRegister #add_item doesn't forget about the previous total
     Failure/Error: expect(cash_register.total).to eq(9.5)
       expected: 9.5
            got: 5.0
       (compared using ==)
     # ./spec/cash_register_spec.rb:35:in `block (3 levels) in <top (required)>'
```

I though that I must be missing something, I was sure that when I was adding to the total, it was a running total. I looked at the soloution on github. It looked like this:

```

class CashRegister

  attr_accessor :items, :discount, :total, :last_transaction

  def initialize(discount=0)
    @total = 0
    @discount = discount
    @items = []
  end

  def add_item(title, amount, quantity=1)
    self.total += amount * quantity
    quantity.times do
      items << title
    end
    self.last_transaction = amount * quantity
  end
```

I could not figure out what quantity.times do etc... had to do with keeping track of the total.

Finally, after days of frustraition I decided to ask a question, though i didn't feel like I had much code to share. Immediatly Enoch pointed out my mistake, and everything fell into place. A good reminder to just check all my operators over and over!




