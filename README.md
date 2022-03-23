# Fellowship-AI-Computer-Vision-Challenge
# Answering the question hints for the challenge
# 1.	Ask yourself why would they have selected this problem for the challenge? What are some gotchas in this domain I should know about?

This problem was chosen since it focuses on a machine learning algorithm which is relative to the fellowship program, namely the Neural Transfer algorithm from the PyTorch library. The main gotcha in this challenge is resizing the image and getting the same size for the two images. When running the program, it seems for some images the styled and content images don’t seem to mix well, so after careful consideration on picking the right images, I was able to complete the challenge.
# 2.	What is the highest level of accuracy that others have achieved with this dataset or similar problems / datasets ?

I saw many Youtube Videos on TensorFlow and PyTorch on using this algorithm and it gave me a perspective on how to tackle the problem. 
# 3.	What types of visualizations will help me grasp the nature of the problem / data?

Using abstract art for the style image would do for a great blend between the two images. Abstract art has a lot of shapes and colors so I thought that visualization would be tough for the algorithm to mix, instead you could still see the resemblance of the white tigers face on the styled output.
# 4.	What feature engineering might help improve the signal?

Content Image and Style Image are the two main features, the engineering required for a better styled output is working with the two loss terms, Content Loss and Style Loss.
# 5.	Which modeling techniques are good at capturing the types of relationships I see in this data?

Neural Style Transfer.
# 6.	Now that I have a model, how can I be sure that I didn't introduce a bug in the code? If results are too good to be true, they probably are!

If during debugging there seemed to be no bug in the code then there probably wasn’t, especially if your program didn’t crash.
# 7.	What are some of the weaknesses of the model and and how can the model be improved with additional work

The main disadvantage for this model is slow progress of training it, because of this the image often isn’t stylized well so trying new project environment like anaconda, pycharm, google colab and Jupyter notebooks, yields different levels of accuracy. Besides the discrepancies in spatial constraints, the model on any environment after multiple iterations yields better results.
