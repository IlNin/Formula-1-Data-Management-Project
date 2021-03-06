# Formula-1-Data-Management-Project
A project that involves Data Integration and Big Data technologies to make some analysis on the current performance of Ferrari in Formula 1 based on real data statistics.


<b>Talend Portion:</b><br/>
Using a dataset that contains statistics from the entire history of Formula 1, I integrated the data I needed for my analysis using Talend Open Studio. The tool was very intuitive to use and I could easily translate my GAV mappings from paper to reality thanks to it. In the "Talend" folder you can find the source code and the datasets I used to perform the integration, and if you want to use them, you need to import them in the "workspace" folder of your local Talend installation folder. There may be issues with the local paths of the input/output files, but it's something that you can easily fix just by using Talend itself.<br/>
I also uploaded the PowerPoint and PDF slides that I used when I presented this project, so you can see the original GAV mappings and how they translated in the project itself.


<b>Neo4j Portion:</b><br/>
Once integrated the data, I uploaded the results to a local Neo4j Graph Database, in order to be able to make queries that are easy to write and understand thanks to its internal Cypher language. Also seeing all of your data in the form of nodes and relationships is quite satisfying. I didn't upload the database to GitHub, but if you want to replicate that, you can follow the commands I used in my presentation, step by step. Just place the contents of "BigData" (inside the "Talend" folder) in the "import" folder of your local Neo4j database, since they contain the integrated data ready to be uploaded to the graph.


<b>Comments:</b><br/>
This was a blast to work with! As a recent Formula 1 fan, it was also a good way to learn more about the history of this discipline. The only moment I had a really hard time with was when I had to convert from the "mm:ss.SSS" format to milliseconds (and vice versa) in some data in order to carry out specific operations, both in Talend and Neo4j funnily enough, which was way more tedious than I had expected. However the thing I was worried about the most was the tone of my presentations, which I did in-character and by pretending I was the new Team Principal at Ferrari. I thought it was a good way to explain the topic, but there was a good risk that the teachers may have found them too off-putting due to their humour and colloquial tone.<br/>
Thankfully it didn't happen! :D
