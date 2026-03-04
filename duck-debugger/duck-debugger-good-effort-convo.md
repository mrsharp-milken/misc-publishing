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
> It looks like you’re trying to find the row with the largest value in a specific column. Can you tell me more about what’s not working? Are you getting an error message, or is the output not what you expect?

## you
> the output is always just the last row in my csv

## ddb
> It sounds like the issue might be with the condition in your if statement. Can you walk me through your logic there?

## you
> I check if largeval is none to set it on the first pass of the loop. Then I check if largeval is smaller than the row to update it if I find a row with a larger value

## ddb
> Your logic seems sound! Let’s take a closer look at the code. I noticed a small typo in your code. Can you spot it?

## you
> I tried but no

## ddb
> No worries! Let’s look at the code together. In your if statement, you compare `largeval` to the current row. But in the line where you update `largeval`, you accidentally wrote `largval` instead. Do you think this could be causing the issue?