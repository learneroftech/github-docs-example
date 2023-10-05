# Writing Good Documentation

## Step 1 - Using Codeblocks.

Codeblocks in markdown make it *very easy* for tech people to **copy, paste, share** code.
A good __Cloud Engineer__ uses Codeblocks whenever possible.

Because it allows others to copy and paste their code to replicate or research issues.


- In order to create codeblocks in markdown you need to use three backticks (`)
- Not to be confused with single quotation (')


```ruby
def factorial(n)
  if n == 0
    return 1
  else
    return n * factorial(n - 1)
  end
end

# Test the factorial function
number = 5
result = factorial(number)
puts "The factorial of #{number} is #{result}"
```

Make note of where the backtick button is located. 
It should appear above the tab key, but it may vary based on your keyboard layout. Check out this random image:
<img width="500px" src="https://github.com/learneroftech/github-docs-example/assets/145515536/c1163938-ac13-41d6-a804-a892c574559b" />
