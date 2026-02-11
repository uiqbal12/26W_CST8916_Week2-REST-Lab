# Youtube video link 
https://www.youtube.com/watch?v=KIp0WZYGRbk


# Assignment 1 submission 

All the paths that were configured were found to be working in local. However, when deployed as an app service finally, which took multiple attempts due to Azure portal glitches. It was found that the put and the delete paths were giving a status of 301. Some debugging was done but was not able to get to the root of the problem. I believe it is because Post and Put and Delete requests were not configured to go through on the app service which may need to be done in azure portal. 

However, when tested locally, these pathways worked just fine. 

