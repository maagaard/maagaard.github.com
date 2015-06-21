---
layout: post
title: "NSProgress in iOS 8 with Swift"
description: "Using NSProgress for progress handling"
category: iOS
tags: 
---

##NSProgress##


{% highlight swift %} 
let progress = NSProgress(parent: nil, userInfo: nil)
{% endhighlight %}


####Example####

{% highlight swift %}  

init() -> NSURLSessionDownloadTask {
    

}

func downloadTask() -> NSProgress {

    let progress = NSProgress(parent: nil, userInfo: nil)

    return progress
}
    
{% endhighlight %}


####Observing NSProgress####