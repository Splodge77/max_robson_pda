### Testing task 1:

# Carry out static testing on the code below.
# Comment on any errors that you see below.
```ruby
### Testing task 2 code:

# Carry out dynamic testing on the code below.
# Correct the errors below that you spotted in task 1.

require_relative('./card.rb')
# file path did not have required prefix
class CardGame


  def checkforAce(card)
    if card.value = 1
      return true
    else
      return false
    end
  end

  def highest_card(card1, card2) # missing comma
    # typo, was dif highest_card
    if card1.value > card2.value
      return card1
      # card does not have 'name' attribute
    else
      return card2
      # else needs explicit return
    end
  end
  # end was in the wrong place

  def self.cards_total(cards)
    total = 0 # total needs to start with a value
    for card in cards
      total += card.value
      return "You have a total of" + total
    end
  end
end


```
