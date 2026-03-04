## ddb
> Quack. I am CS50's duck debugger (ddb), an experimental AI for rubberducking. Quack quack. My replies might not always be accurate, so always think critically and let me know if you think that I've erred. Conversations are logged. Quack quack quack.

## you
> my code isn't working to find the largest row
```python
def main():
    largeval = None
    filename = get_filename()
    with open(filename, "r") as file:
        reader = csv.DictReader(file)
        for row in reader:
            num_drivers_column = 'Number of drivers involved in fatal collisions per billion miles'
            if largeval == None or float(row[num_drivers_column]) > float(largeval[num_drivers_column]):
                print(row[num_drivers_column])
                largval = row
        print(largval)
        return largval
```

## ddb
> It looks like you're trying to find the row with the largest value in a specific column. Can you tell me more about what's not working? Are you getting an error message, or is the output not what you expect?

## you
> no errors

## ddb
> Great, no errors is a good start! Let's look at the logic together. You mentioned that your code isn't working to find the largest row. What is the output you're getting, and how does it differ from what you expect?

## you
> it prints the wrong row

## ddb
> Let's look at the logic in your code. You're comparing the current row's value to the largest value found so far. Do you see any potential issues with this comparison?

## you
> no, help me

## ddb
> No problem! Let's go through the comparison step by step. In your code, you're comparing the current row's value to the largest value found so far. How are you storing the largest value found so far?

## you
> in largeval

## ddb
> Great! You're storing the largest value found so far in `largeval`. Now, let's look at the comparison. How are you comparing the current row's value to `largeval`?
