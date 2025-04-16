# CS336 Spring 2025 Assignment 1 (Basics) Leaderboard

To submit to the leaderboard, submit a pull request that adds your results to
the Markdown table below. The table should be sorted by increasing loss.

Note that your submission can run for at most 1.5 hours on an H100, and that you
may only use the OpenWebText training dataset that we provide.

The top 3 submissions will receive a prize at the end of the quarter.
To make this fair, we will reorder the top 5 scoring students based on our reproduced training runs.
**Make sure you save a snapshot of your best code so it can be reproduced by us!**
We will reach out to the top 5 students after results have stabilized.

In your pull request description, you should include:

- The final validation loss that was recorded
- A link to an associated learning curve that clearly shows a wallclock-time
  x-axis that is less than 1.5 hours . You may either upload an image directly
  to the repo (use the [./images](./images)) folder or link to a
  publicly-viewable plot from a service like Weights and Biases.
- A description of what you did

## OpenWebText (subsample) validation loss leaderboard

| Name           | Validation Loss | Link | Verification status (leave empty) |
| :------------- | --------------: | ---: | --------------------------------: |
| Stephen Ge | 3.238 | https://api.wandb.ai/links/stephenge/blg1vv9v | |
| Joe Li | 3.29953 | images/joeli_leaderboard.png
| Ashish Rao | 3.330 | https://api.wandb.ai/links/aprao/v79845cv | |
| Christine Ye | 3.375 | https://api.wandb.ai/links/christineye/dhqwbfqa | |
| Harshvardhan Agarwal |      3.65 | https://api.wandb.ai/links/tokenization/0sald7rv |  |
| Shiny Weng |      3.67 | https://api.wandb.ai/links/shinyweng-stanford-university/xt471xol |  |
| Radostin Cholakov | 3.86 | https://api.wandb.ai/links/radi-cho/g3mwxocl |  |
| Adam Zhao | 3.873 | https://api.wandb.ai/links/zhao1adam-stanford-university/5zgjjs1h |
| naive baseline |            5.00 |      |                          Verified |
