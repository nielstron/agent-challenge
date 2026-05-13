## Challenge

In this folder you find `train.csv` and `val.csv`. Your task is simple: Produce a good model of the last column based on the first four columns.
Your solution should be a script that can be run like this:

```python
python3 predict.py input.csv
```

Where `input.csv` will be the final verification file that contains only the first three columns. The script should output the fourth column in the same order as the inputs.


Good luck!

### Coding Agents 101

If you have not done so yet, download and install Codex from this link: https://developers.openai.com/codex/cli
Open a terminal on your computer to start the agent like this:
```
codex
```

Use the provided API-key to authenticate.
Feel free to use the Codex App instead (only available on Mac).
I recommend using the default settings (latest model, medium reasoning).


### AGENTS.md

If you notice that your agent repeatedly makes the same mistake it *might* help to create a file `AGENTS.md` and insert hints or comments. It *might* also confuse the agent instead, since this file will always be loaded upon agent initialization. So tread carefully!
