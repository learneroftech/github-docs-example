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

- Make note of where the backtick button is located. 
- It should appear above the tab key, but it may vary based on your keyboard layout.
- Check out this random image:

<img width="500px" src="https://github.com/learneroftech/github-docs-example/assets/145515536/c1163938-ac13-41d6-a804-a892c574559b" />

Good Cloud Engineers use codeblocks for both Code and Erros that appear in the console.




```bash
Traceback (most recent call last):
        2: from /usr/bin/irb:23:in `<main>'
        1: from (irb):1
RuntimeError: This is a custom error message
```

> Here is an example of using a codeblock for an error that apears in bash.

## Step 3 - Use Github Flavored Markdown Task Lists

Github extends Markdown to have a list where you can check off items. <sup>[1]<sup/>

- [x] Finish Step 1
- [ ] Finish Step 2
- [x] Finish Step 3

# Step 4 - Use Emojis (Optional)

Github Flavored Markdown(GFM) supports emoji shortcodes.
Here are some examples:

| Name | Shortcode | Emoji |
| --- | --- | --- |
| Cloud | `:cloud:` | :cloud: |
| Cloud with lightning | `:cloud_with_lightning:` | 🌩️: |

# Step 5 - how to create a table

```markdown
| Name | Shortcode | Emoji |
| --- | --- | --- |
| Cloud | `:cloud:` | :cloud: |
| Cloud with lightning | `:cloud_with_lightning:` | 🌩️: |
```

## References

- [GitHub Flavored Markdown Spec](https://github.github.com/gfm/)
- [Basic writing and formatting syntax (Github Flavored Markdown)](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
- [GFM - Tasks Lists](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#task-lists) <sup>[1]<sup/>
- [GFM - Emoji CheatSheet](https://github.com/ikatyang/emoji-cheat-sheet)
