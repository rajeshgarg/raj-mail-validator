gem install raj-mail-validator
  or
gem 'raj-mail-validator'

How to use

add :valid_address=>true to object attribute
eg
User.rb

validate :email, :valid_address=>true

tested for rails3 