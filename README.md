
# project idea
The goal would be to point the app at any web page and ask questions about the page. The questions and the answers will be saved to a database. But, after some testing, the roberta model can barely answer direct questions. Many more things to learn here!

# question
How to build a smarter model? 

---


To run this use:
```streamlit run app.py```
In the /src dir

---

You'll need to install streamlit

``` pip install streamlit```

---

and transformers

```pip install transformers```

---

and pytorch

```pip3 install torch-tensorrt -f https://github.com/pytorch/TensorRT/releases```

---

I tried running the app with pytorch installed and the app complained. So I installed tensorflow. TF is huge so prepare to wait.

https://www.tensorflow.org/install/

```pip install tensorflow```

Hopefully one of these 'transformers' will work!

--- 

After much fussing, I got the app to work. The ability of the app to interpret the web pages was weak though. I'm not sure what would be required to 'train' the model to better interpret the data!


# inspired by
https://medium.com/better-programming/create-a-wikipedia-question-answering-app-with-python-2401e1789d6c#ade3

Thank you!