# Linkedin Post

<!-- Spotlight the AI Reporter tool and its ability to provide insights and recommendations based on log analysis. -->

As part of the toolset that Doppler provides for developers to effectively monitor and diagnose issues in their applications, one of Doppler's more interesting tools is it's AI Reporter feature.

The AI reporter feature was very important to me to implement as I, and I'm sure nearly every other developer on the planet, has benefited greatly from the rise of Large Language Models (LLMs) such as ChatGPT and Claude, with regards to productivity both in developing and debugging software. While LLMs have not yet been fully trusted with the responsibility of building our software, they have definitely served as great companions in the short time they've been around.

This is why we worked very hard to bring the power of LLMs into Doppler, to enrich the developer experience and be able to take better advantage of the capabilities of Artificial Intelligence and LLMs as a tool to boost productivity in software development.

The implementation of this feature was challenging as well as educative and gave us the opportunity to learn more deeply about the internal operation of these Large Language Models and how to bring them to life in our applications.

One of the challenges we faced was the cost of running the LLM. Most platforms offer paid APIs which can be integrated in our applications. However, one of our guiding principles is to keep Doppler as inexpensive as possible to run so that we can eventually offer nearly free/very affordable services to our users. Also, we don't have a lot of money to spend.

This led to more research and we were able to come up with a solution by deploying our LLM on HuggingFace, The AI community building the future. HuggingFace's platform allowed us to be able to acquire and deploy our own model for completely free. 

This allowed us to have complete control over the operation of the model and the data, ensuring confidence in the privacy of our information and that of our users. Consequetly, because it is also not free, this introduces performance issues, as LLMs require intensive computing to be able to perform at meaningful scale. However, this is something we are hopeful to have optimized in the nearest future.

As at now, the AI reporter is able to analyse logs and provide concise and helpful analysis, pointing developers to the right path in resolving their issues faster. In the future, it will be able to pre-empt these issues by monitoring the trend of application logs and take pre-emptive measures such as notifying ahead and raising alarms. These are just a few of the interesting directions we're planning to go in the nearest future.

AI has proven to be a great asset, especially for developers both in developing and debugging software and we hope to be able to do more with it in future updates to the platform.

If you want to try out HuggingFace for integrating LLMs or other forms of AI models into your own applications, check out this article by Gathnex: https://gathnex.medium.com/how-to-deploy-llm-for-free-of-cost-6e7947d9b64a

There's still time to join the waitlist! Sign up now at https://usedoppler.app and join us on this exciting journey.