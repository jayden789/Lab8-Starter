# Lab8-Starter

# Members:
Christopher Schrader, Thanh

# How are graceful degradation and service workers related?

Service workers are related to graceful degradation because they help us maintain as much functionality of our website as possible with cached data. So, if someone loses internet and goes offline, the website will still be somewhat presentable even though they are no longer able to load any new data. If the website is reliant on a lot of fetch requests that request data that is changing, our website will no longer be functional. However, you would still be able to see a "snapshot" of what the website looked like with the cached data before a user's internet went out.

[pwa](PWA.png)
