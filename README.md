## This reposity records the learning process of serveless
# Describtion of serveless
Suppose a senario like this, you deploy a app in a public cloud which provide a api.
The app is default to be paused unless you called the api, and the public cloud provider would then warn up your app to service for the api call,
during this period, if your request is too much, the cloud provider would automatlly scale your app, after the api call finished, your app would then remain paused or terminated. 
Under such senario, you should only pay for the call of api.If you just leave your app on the infrustracture of the cloud and never call it, you need not pay for anything.
I think this is the senario of serveless.
