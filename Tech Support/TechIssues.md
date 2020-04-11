---
title: Tech Support
has_children: False
nav_order: 4
---

## Pytorch

- [A detailed example of how to generate your data in parallel with PyTorch](https://stanford.edu/~shervine/blog/pytorch-how-to-generate-data-parallel)

   A tutorial that shows how to efficiently load data into your GPU PyTorch Models.

-  
## Amazon EC2

- [azdaly's](https://github.com/azdaly) Brief Tutorial to getting a Jupyter Notebook running on EC2
  - The trick is to do [this](https://docs.aws.amazon.com/dlami/latest/devguide/setup-jupyter-config.html) (on your EC2 instance). 
  - Then to do [this](https://docs.aws.amazon.com/dlami/latest/devguide/setup-jupyter-start-server.html) (also on your EC2 instance).
  - Then do [this](https://docs.aws.amazon.com/dlami/latest/devguide/setup-jupyter-configure-client-linux.html) (on your local machine).
  - Finally copy and paste the localhost value (often https://localhost:8888) into a web browser.

- [Run Project Jupyter Notebooks On Amazon EC2](https://chrisalbon.com/aws/basics/run_project_jupyter_on_amazon_ec2/)

  A different and more comprehensive guide to getting access to jupyter on EC2.
