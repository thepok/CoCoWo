# CoCoWo
An automatic **Co**de**CoWo**rker that with the help of Deep Recurrent Neural Networks predicts the next codechanges the programmer intends.

## Dream
When i write Code, i allways think: "Man again i have to write this code, that i have written a thousand times, and other Programmers millions of times.... it must be possible, to automate this". And for sure, while programming, manny repetive tasks have to be done: Filter a list, write some properties or common Utility-Functions and many other things. I belive with Deep Recurrent Neural Networks and other machine learning techs we should slowy be able to reach this aim. Imagine the incrased productivity when such a tool would be freely aviable. The best: With every Scintific progress or improved Hardware the Predictions become better and better. 

## Ideas
- An End to End aproch would be great, but i belive if we make the life of the neural net easier with specially prepered Input, not to much potential of the Net has to be wasted, to learn the specialities of an Programminlanguage
   * provide syntaxtrees or other usualy anyway by the compailer generated Informations
- Writing a Comment could be enough to guide the CoCoWo to generate some corosponding useable Code.
- Training should be two parted:
   * One general training on a global Codebase
   * Second one on the Codebase from the current Project or related ones
   * Or the prediction of two Networks, a specialiezed one and a generall one are merged
- Codecreation should not be restricted to the current Position in the Sourcefile
   * For example in C++ there exist .cpp and .h files that are strongly related. Code should be placed in both files simulatnly.
- Multilayerd aproach
  * one net could create the General Structure of the SourceCode and another fills it with life
   
## Benefits
- The use of the Cocowo could lead to better readable code
- Less repetive Work 

## Inspiration
Andrej Karpathy generated in [The Unreasonable Effectiveness of Recurrent Neural Networks](http://karpathy.github.io/2015/05/21/rnn-effectiveness/) some impressiv real looking C++ Quellcode frome the Sourcecode of Linux

## Readingmaterial
- [Understanding LSTM](http://colah.github.io/posts/2015-08-Understanding-LSTMs/)
- [Attention and Augmented Recurrent Neural Networks](http://distill.pub/2016/augmented-rnns/)

## Proposed Roadmap

### 1 Decide on Framworks

- Propably Tensorflow

### 2 Get Framework running
- optimaly on Linux and Windows

### 3 Prove principle on easy Testcase
#### 3.1 Write Prototype
- generate Sourcode in an very easy specialy invented programminglanguage
- try prototype and finetune hyperparameters

### 4 Productionsystem

#### 4.1 Collect real Trainingdata
- maybe it is usefull to use commithistories and not only the final Sourcecodes to give the System an Idea in what way Sourcecode develops

#### 4.2 Training

#### 4.3 Apply System in realworld situations

### 5 UI for common IDEs

#### 5.1 Design
#### 5.2 Implemention for Eclipse and Visual Studio 

