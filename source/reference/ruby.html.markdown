#Ruby Reference

Try the things in this reference. Go to your terminal and type `irb`, then press enter. You will be
in an `interactive ruby (irb)` session.

In Ruby, anthing after a `#` is ignored by the computer. This is called
`commenting`

Any time you see `#=>` that is what will be returned when you press `enter`


### Strings

```ruby

  # Strings are created by putting quotes (") around one more words

  "Hello" #=> "Hello"

  "Hello my name is Hashrocket" #=> "Hello me name is Hashrocket"

  "Goodbye" #=> "Goodbye"

  "Hello" + "Goodbye" #=> "HelloGoodBye"

  "Hello".reverse #=> "olleH"

  "Hello"[4] #=> "o"

  "Hello"[0..2] #=> "Hel"

  # interpolation
  "Hello#{3+7}" #=> "Hello10"

```

### Numbers - Integers and Floats
__Note:__   In programming, the `+`, `-`, `/`, `*`, etc.. are all called `operators`.

```ruby

  # Integers are created by using just numbers (0-9)

  123 #=> 123

  # Floats are created by using numbers with a decimal/period (.)
  12.4 #=> 12.4

  # add integers
  1 + 1 #=> 2

  # add an integer and a float
  1 + 1.5 #=> 2.5

  # subtract integers
  5 - 10 #=> -5

  # division
  4 / 2 #=> 2

  # multiplication
  10 * 8 #=> 80

  # modulus (this is like getting the remainder)
  15 % 4 #=> 3

```
