<h2> Training exercises for Cloudera's Distribution for Hadoop; Cloudera is a Hybrid Data company. </h2>

-------------------------------------------------------------------------------------------------------

<p>Cloudera's distribution for Hadoop provides a number of services</p> 
<p> This includes:- </p>
<ul>
         <li>HBase</li>
         <li>Hue</li>
         <li>Impala</li>
         <li>Oozie</li>
         <li>Spark</li>
      </ul>
      
-------------------------------------------------------------------------------------------------------- 
<p><h3><li>HBase</li></h3></p>

<p><li>Workflow scheduler system to manage Apache Hadoop jobs.</li></p>
<p><li>Oozie Coordinator jobs.</li></p>
<p><li>Supports: MapReduce, Pig, Apache Hive, and Sqoop .</li></p>
<p>Workflows in Oozie are defined as a collection of control flow and action nodes in a directed acyclic graph. Control flow nodes define the beginning and the end of a workflow (start, end, and failure nodes) as well as mechanism to control the workflow execution path(decision fork and jon nodes).</p>

--------------------------------------------------------------------------------------------------------

<p><h3><li>Hue (Hadoop User Experience)</li></h3></p>
<p> Hue is a web-based interactive query editor that enables you to interact with data warehouses. For example, the following image shows a graphic representation of Impala SQL query results that you can generate with Hue. </p>

![image](https://user-images.githubusercontent.com/97665556/216337193-b285a3c3-2703-4e1a-b14d-988fd4b948c7.png)
<p> You can use Hue to:- </p>
<p><li><b>Explore, browse and import your data </b> through guided navigation in the left panel of the page: </li></p>

![image](https://user-images.githubusercontent.com/97665556/216339073-83dd625a-b69c-46e9-af88-1bd4db8a7f97.png)

<p>This panel enables you to: </p>
<ul>
         <li>Browse your databases</li>
         <li>Drill down to specific tables</li>
         <li>View HDFS directories and Cloud storage</li>
         <li>Discover indexes and HDFS or kudu tables</li>
         <li>Find documents</li>
 </ul>
 
 <p>Objects can be tagged for quick retrieval, project association, or to assign a more "human readable" name if desired. </p>
 <p><b><ol><li>Query your data, create a custom dashboard or schedule repetitive jobs</li></ol></b> in the central panel of the page. </p>
 
 ![image](https://user-images.githubusercontent.com/97665556/216589222-22ee4f15-d084-4503-8699-95222a4106f3.png)

<p> The central panel of the page provides a rich toolset, including:- </p>
<p><ul><li><b>Versatile editors </b>that enable you to create a wide variety of scripts. </li>
         <li><b>Dashboards </b>that you can create "0n-the-fly" by dragging and dropping elements into the central panel of the Hue interface. No programming is required. Then you can use your custom dashboard to explore your data. </li>
         <li><b>Schedulers </b>that you can create by dragging and dropping, just like the dashboards feature. This feature enables you to create custom workflows and to schedule them to run automatically on a regular basis. A monitoring interface shows the progress, logd, and makes it possible to stop or pause jobs. </li>
         </p>
         
         
<p><li><b>Get expert advice on how to complete a task: </b></li></p>
         
![image](https://user-images.githubusercontent.com/97665556/216936755-53522b4a-72a5-454a-ab27-42e6eb99171b.png) 

         
<p>The assistant panel on the right provides expert advice and hints for whatever application is currently being used in the central panel. For example, in the above image, Impala SQL hints are provided to help construct queries in the central panel. </p>

<p><h3><li>Impala</li></h3></p>
<p> Impala provides fast, interactive SQL queries directly on your Apache Hadoop data stored in HDFS, HBase, or Amazon Simple Storage Service (S3). In addition to using the same unified storage platform, Impala also uses the same metadata.


