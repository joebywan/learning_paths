# How to ask a question?

## How to ask a question?

When seeking assistance, people are eager to help, but your responsibility as the seeker of help is that you ensure you’re doing the legwork before asking.

### Before you ask:

#### Get to the root of the problem
When in the flow of things and hitting a wall you can usually run into a problem, and not realise the root of the issue until you stop and think.  

So… stop and think. Articulate the problem, and write it down with pen and paper if you need to. This is normally called [Rubber Ducky debugging](https://en.wikipedia.org/wiki/Rubber_duck_debugging).

#### Document your progress
When you call your ISP because the internet’s down, and you’ve already turned the modem off and on again, but they ask you to do it again, it’s frustrating. To avoid this sort of situation, as you’re working, have a note open. Confluence gives you access to a personal space, which is great for note taking. If you’ve documented what the problem is, and how you’ve tried to solve it so far, then when you go and ask for help, you’ll be able to show exactly what you’ve done. It’ll stop you covering travelled paths, and speed up time to resolution.

#### Have you searched?
Ensure you’ve hit a search engine to try and find the information you’re looking for. There’s plenty of depth to the Google search syntax, here’s a short primer: [How to Google like a Pro – 10 Tips for More Effective Googling](https://www.freecodecamp.org/news/how-to-google-like-a-pro-10-tips-for-effective-googling).

If you’re looking for a specific error message, as an example, try including parts of the error message, such as keywords, in your search. If you have an exact phrase that is relevant, include that in double quotes (`"`). If I’m receiving the error message below when trying to bootstrap an AWS CDK stack:

    Error: Need to perform AWS calls for account 012345678912, but no credentials have been configured


You might try googling for the following:

    aws cdk stack “no credentials have been configured”


Resources such as GitHub issues, StackOverflow, and official documentation discussing your specific question or issue can be found and help you to determine your next steps.

### Before you ask:
- Get to the root of the problem
- Document your progress
- Have you searched?
- Read the manual?
- Checked the wiki?
- Tried ChatGPT?

---

### Read the manual?
Many technologies, such as AWS CDK, Terraform, and Python, have well-maintained documentation written by the developers of the service.

Documentation such as how to use the TypeScript AWS CDK module for EC2 instances can be found with a simple Google search:

    aws cdk v2 typescript ec2


Which would lead you to the [AWS CDK documentation](https://docs.aws.amazon.com/cdk/api/v2/docs/aws-cdk-lib.aws_ec2-readme.html) for the `aws-cdk-lib.aws_ec2` module as the first result.

### Checked the wiki?
If you're in the industry, your workplace should have a wiki.  Make sure what you’re after hasn’t already been documented there. If it’s not, consider adding an article for it. is a great place to drop knowledge. The more you add answers to questions in there, the better it will be. You get out what you put in. It’s a good practice to start a knowledge base article when you don’t know something—it doesn’t have to look pretty, but if it has the info in there, it can get neatened up later.

For more information on a way I advocate for building knowledge bases in an operational role: [What is knowledge centered service (KCS)?](https://www.atlassian.com/itsm/knowledge-management/kcs)

### Tried ChatGPT?
[ChatGPT](https://chat.openai.com/) can be a great tool for getting answers. However, any answers must be taken with a grain of salt or verified elsewhere. It is good practice to verify any results with Google etc. afterward.  For more information, use your newfound google skills to research Large Languange Models or LLM.

---

### Ok, you’ve tried all that? Now what?
Well, now that you’ve clarified and articulated the problem, documented your attempts at resolution, and utilized multiple methods to locate the answer, you’re well-equipped to go and ask for help. This will signal to the person you’re asking that you value your time by ensuring the easy questions aren’t being asked.

---

For more information:
- [How To Ask Questions The Smart Way](http://www.catb.org/~esr/faqs/smart-questions.html) - A much older version, developed separately, but very comprehensive that it stands today.

---

**Note:**  
Assume LLMs, such as ChatGPT, retain all of the data that you supply.  

Make sure you don’t supply any LLM with client information, credentials, or other privileged/confidential data. Sanitize the code you paste, or construct any questions that you ask to be generic.
