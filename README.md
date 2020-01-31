# SuperMemo
A collection of helpful tools for the Spaced Repetition application, SuperMemo

The Question and Answer file contains the JavaScript single line that results in your Question referencing a question HTML file and your answer referencing an answer HTML file.

## Why
I've been using SuperMemo off and on over many years.  When I use it regularly it works very well.  One of my main problems has been the presentation of data.  There is a lot of detailed information in the SuperMemo FAQ on how to present data through templates.  I always thought that this could be improved but was not sure how.  

Then one day it hit me.  Why not leverage the world-wide standard used by web developers to present the data and of course this would be with HTML files and JPEG files that I would create and organize within a directory structure of my choosing on my local hard-drive.  I would also use CSS and JavaScript.

## How to Use
1. Create a directory structure that makes sense to you and place it in an easily accessible directory location on your drive.  As an example, in Windows, your best bet is something like

  `C:/Data/Knowledgebase/Training/`

2. Create your Question HTML file and your Answer HTML file.  There are many substeps involved.  More info to come later.

3. Create your SuperMemo Q & A file for import into SuperMemo.  The intent is to reference your existing HTML files and the format is like this:

```Q: Test Question 1 from TOPIC_NAME
Q: <script language="javascript">window.location.href = "file:///C:/Data/Knowledgebase/Training/Question1.htm"</script>
A: <script language="javascript">window.location.href = "file:///C:/Data/Knowledgebase/Training/Answer1.htm"</script>```



