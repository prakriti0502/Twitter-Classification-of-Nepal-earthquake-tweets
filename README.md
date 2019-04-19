# Twitter-Classification-of-Nepal-earthquake-tweets
<h2>Classification of Nepal Earthquake Tweets Using Machine Learning Algorithms</h2>

Microblogging sites like Twitter are increasingly being used for aiding relief operations during various mass emergencies.
A lot of critical situational information is posted on microblogging sites during disaster events.
However, messages posted on microblogging sites often contain rumors and overstated facts.
In such situations, identification of factual or fact-checkable tweets, i.e., tweets that report some relevant and verifiable fact (other than sympathy or prayer) is extremely important for effective coordination of post-disaster relief operations.
Additionally, cross verification of such critical information is a practical necessity and resource availability.
Hence, automated Machine Learning techniques are needed to identify the tweets that talk about the need of resources or availability of resources. 

<h2>Problem Statement:<h2>

Our aim is to Classify tweets whether it doesn't talk about any resources needed/available(irrelevant tweets) or
it mentions a resource that is needed(Need tweets) or
it mentions a resource that is available(Availability tweets)

<h2>Class Description:</h2>
<ul>
  <li>0:The tweet doesn’t talk about any resources needed or available(Irrelevant tweets)</li>
  <li>1:The tweet mentions a resource that is needed (Need Tweets)</li>
  <li>2:The tweet mentions a resource that is available(Availability tweets)</li>
</ul>



<h2>Observations:</h2>
<ul>
  <li>There are a lot of irrelevant tweets(class 0) and a few Needed and Availablity Tweets.</li>
  <li>Since irrelevant tweets are in large proportion, data is skewed.</li>
</ul>
