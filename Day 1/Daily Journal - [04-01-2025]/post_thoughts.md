## Thoughts After Completing Work

It was one hell of a day! My model is currently achieving **25% accuracy** on my test set, which is disappointing. 

### Achievements
- **Completed Aims**: Successfully met all the goals I had set for the day.

### Difficulties Faced (Learnings)
1. **Learning Kaggle**: Initially, I struggled with understanding the Kaggle platform. It took around 30 minutes to figure out how to import datasets, but copying the dataset paths from their cloud made it manageable.
2. **Handling Large Classes**: The dataset had many classes, which made manual handling infeasible. I solved this by using Python's `os` and `pathlib` libraries to extract directories names dynamically and after a lot of f-string i was able to make my dataset.
3. **RAM Overflow**: Resizing images to 600x600 caused memory issues. After some brainstorming i thought of directly appending array inside a array as array takes less memory but that was not possible. After almost wasting 2hrs trying this approach and almost giving up , it finally hit me and i resolved it by resizing the images to 100x100, which reduced memory usage significantly.

### Interesting Insights
- Using `pathlib` in Kaggle returned **PosixPath** objects, indicating that Kaggle operates on a Linux-based system. Meanwhile, on my local machine, I use Windows paths. A small but interesting discovery!

---


**Bye Bye!**