# **README**

## **Introduction**

Sparkify is a digital music application that enables users to listen to music online. Currently, the application aims to offer new content to users based on their song preferences. However, the information related to users and their activity are stored in CSV files, see Figure 1, which avoids querying data and therefore running analytics on it. 

![sparkify schema](/images/image_event_datafile_new.jpg)
**Figure 1** Example of CSV file content.
<br />


---
## **Explanation of the files in this repository**

The following table describes the content of this repository. 

<table>
  <tr>
   <td><strong>File</strong>
   </td>
   <td><strong>Description</strong>
   </td>
  </tr>
  <tr>
   <td>Project_1B_ Project_Template.ipynb
   </td>
   <td>Jupyter notebook that creates step-by-step the required tables for the given queries.
   </td>
  </tr>
  <tr>
   <td>event_datafile_new.csv
   </td>
   <td>CSV files that contains and gropus all data records from the event_data folder. 
   </td>
  </tr>
  <tr>
   <td>event_data
   </td>
   <td>Folder that contains data in a CSV format. 
   </td>
  </tr>
  <tr>
   <td>README.md
   </td>
   <td>File that contains the main information and instructions of how to use this repository. 
   </td>
  </tr>
  <tr>
</table>

---
## **Prerequisites**

Before using this repository, you must comply with the following:

*   Install the **latest stable version of Cassandra** (release: 3.11.10) in your local machine.  
The installation option followed in this project was the [binary tarball](https://cassandra.apache.org/doc/latest/getting_started/installing.html#installing-the-binary-tarball) type for iOS. 
*   Install **cassandra-driver** a python wrapper/python driver to run Apache Cassandra queries. Use the following command in your Jupyter notebook:
    ```
    !pip install cassandra-driver
    ```
*   Clone this repository.

