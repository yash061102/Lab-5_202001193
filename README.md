# Lab-5_202001193
# Static Analysis

--> Here i used a mypy tool for static analysis.

--> Here is the file which i taken for analysis:

--> Repolink: https://github.com/qxresearch/qxresearch-event-1/tree/master/Applications/Audio%20Visualization%20Tool

--> First Error:

![image](https://user-images.githubusercontent.com/112205217/225573689-68488ebe-6d8f-4fcc-b656-d6a5f1dc48e3.png)

 --> This error is related to library not found here 'pyaudio' is not present so we can install with the use of pip command.
 
 --> Second error:
 
![image](https://user-images.githubusercontent.com/112205217/225574292-1a091886-c0e5-4370-8fc4-8af881b13998.png)

--> This error is related to numpy library so here numpy is not installed so we can install that library using pip command(pip install numpy).

-->Third error:

![image](https://user-images.githubusercontent.com/112205217/225575061-3ba73f10-dd70-43f1-8ab3-4ebad81a3d0a.png)

--> this error tells about Python interpreter is unable to find "matplotlib.pyplo" this module and this error can be solved by installing this module and for installation we can run this command in terminal(pip install matplotlib).

--> Forth error:

![image](https://user-images.githubusercontent.com/112205217/225576396-40f03863-ebd1-4920-bb22-6a4cd6fe82a6.png)

-->This error is related to python interpreter is unable to find implementation of "matplotlib" library and this error can be solved by installing this module.

-->Now let's take 2nd file for Analysis:

Repolink: https://github.com/ShubhamRathi/Remote-Method-Invocation/blob/master/Server/Server.py

--> Error:

![image](https://user-images.githubusercontent.com/112205217/225580042-1cd54f94-c9f1-45b6-9057-bcf3abe9fe9e.png)

--> This error is related to identation error Specifically the level of identation on line 16 does not match the level of indentation of the surrounding code block. To fix this error we can check identation of code block and make sure that is consistent.For an example, if the surrounding code block is indented with a six space, then line 16 should be indented with a six space.
