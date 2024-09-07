# Arguments

Arguments follow the name of the command and are used to give options to run the command itself. Separate each argument with a space.

![Example of a command executed successfully with all the required arguments.](<../.gitbook/assets/slashrequiredarguments.png>)

## Required arguments

Required arguments need to be input for the command to work correctly. You will not be able to send the command otherwise.

In this guide, required arguments are marked as `<argument>` with the angle brackets. It is important to **not put** the angle brackets in the actual command, as they are used as a placeholder to indicate that an argument is required.

## Optional arguments

Optional arguments are not necessary for a command to work, but they may be used to provide additional information or add extra details to a command. In this guide, they are marked as `[argument]`, with the square bracket not needed.

### Optional arguments with spaces

They are marked with `[...argument]` in this guide. They are joined together and allow spaces in there, unlike other arguments that break up on spaces.

![The reason for the warning is optional.](<../.gitbook/assets/slashoptionalarguments.png>)

## Type of arguments

### Durations

Durations are a combination of numbers and letters representing units of a measure of time: for example, 4w5h means 4 weeks and 5 hours.
Below, you can see a table with all supported abbreviations.

| Duration                   | Supported Abbrevations          |
| -------------------------- | ------------------------------- |
| Week (7 days)              | w - week - weeks                |
| Day (24 hours)             | d - day - days                  |
| Hour (60 minutes)          | h - hour - hours                |
| Minute (60 seconds)        | m - minute - minutes            |
| Second (1000 milliseconds) | s - second - seconds            |
| Millisecond                | ms - millisecond - milliseconds |

{% hint style="warning" %}
If no unit is specified, the bot will default to millisecond
{% endhint %}

![A duration argument.](<../.gitbook/assets/slashtypeofarguments.png>)

![Another example of duration. As you can see, you can extend or reduce the length to a temporary role by adding or substracting time to it.](<../.gitbook/assets/slashtypeofarguments2.png>)
