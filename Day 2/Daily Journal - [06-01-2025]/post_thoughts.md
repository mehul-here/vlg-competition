## Thoughts After Completing Work

It was another hell of a day! My model is currently achieving **25% accuracy** on vlg test set. 

### Achievements
- **Completed Aims**: Successfully met all the goals I had set for the day.
- **Achieved optimum image size**: It was 200 by 200.
- **Posted csv file with predictions on vlg training set**

### Difficulties Faced (Learnings)
1. **Simple bug**: I was having a bug where i was getting accuracy of 1% even on the training set from which the model learnt . It took me almost 1 hour to understand that i was using unscaled set to help the model learn. It costed me a lot of time.
2. **Finding optimum image size**: It took me alot of trial and error to find which image size would not result in ram overflow. Actually , sometimes it looked like ram is not gonna overflow but after scaling , it really shoots up causing error .Second instance where it shoots is when model is intiating. So , next time i will have 10 gb of margin before scaling and model learning.

---


**Bye Bye!**