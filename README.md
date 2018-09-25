
# Working with Lessons on Learn - Lab

## Introduction
Now that we have had an introduction with our command line, how to clone github repos to our local machine (our computer), and some common jupyter notebook operations, it's time to put our skills to the test! Below, follow the instructions to pass the tests for this lab.

## Objectives
* Make changes to a jupyter notebook and push it up to GitHub
* Perform basic computations in a Jupyter Notebook and store them in a variable

## Instructions

Assign the below variable `number` to the number `27` by replacing `None` with `27`.


```python
number = None
number
```

Next, like the above, reassign the `flatiron_mantra` variable with the string `"Learn. Love. Code."`. 


```python
flatiron_mantra = None
flatiron_mantra
```

Finally, in your command line type `python -m pytest` to see if your tests are passing. If you would like to see a more detailed test output, type `python -m pytest -vv` and it will show each test line by line with its name and whether you've passed or failed it. 

Once all your tests are passed, type `git add .`, then `git commit -m "finished lab and all tests are passing"`, and finally `git push`. 

## Making A Pull Request

The last step, in order to pass a lab, is to make a pull request on github. It's relatively straightforward and will become more natural and easy as you go through the course. Just follow the steps below:

**1.** Go back to your github repository your forked and then cloned. Remember we clicked on the github icon at the top of our learn lesson, then clicked fork, which then brings us to our forked repository. Once we are at the forked repo, click on the **`New Pull Request`** button. (You can optionally click the green `"Compare & pull request"` button.

![new_pull_request](make-new-pull-req.png)

**2.** Then we will be directed to a new page where we will click a green `Create pull request` button.

![create_pull_request](create-pull-req.png)

**3.** Which then will direct us to the final page, where we will finally commit our pull request by clicking `"Create pull request"` one more time. Feel free to update or add to your pull request message, but you can simply skip that step and submit the pull request. 

![finish_pull_request](create-pull-req-final.png)

And that's it! You may need to refresh your learn.co lesson page, but your light should be green and allow you to move on to the next lesson as long as you have passed the tests (which we made sure to do before creating our pull request)!

## Summary
Great work! We are well on our way to mastering Jupyter notebooks. We practiced reassigning variables, running cells, checking our outputs, and running our tests to get them to pass.
