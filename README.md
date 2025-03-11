# WechatDatasetProcess
### What's it about?
This repository contains a .ipynb file that manipulate Wechat video channel data, giving a lesser but denser matrix for model training.
### Description
It logic is to get all samples that have at least one positive target among four tagets and randomly add the rest samples to amount of samples. They are "read_comment", "like", "click_avatar" and "forward".
And that reduces its scale from 700k lines of data to 50k, which is suitable for a single machine with 16G RAM to train with.
### Credit
If you want to see the whole project, please leave a star and head to https://github.com/ShowMeAI-Hub/multi-task-learning/blob/main/1.data-preprocessing-and-feature-engineering.ipynb for more~
