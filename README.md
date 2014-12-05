Disclaimer: Birdwatch Application developed by Matthias Nehlson. This is just a fork.

#WorldWatch  
Check out the count from each country on a specific set of topic.

##Setup

Linux:
tested and deployed on Azure by Nagesh:

Step 1:
Install the JDK 

   sudo apt-get install default-jdk

Step 2:
Install & run ElasticSearch REST Service 

  wget https://download.elasticsearch.org/elasticsearch/elasticsearch/elasticsearch-1.4.1.tar.gz
  tar -xvf elasticsearch-1.4.1.tar.gz
  elasticsearch-1.4.1/bin elasticsearch

Step 3:
Build the Angular Web App
   
  #Install node package manager
  sudo apt-get install npm

  #resolve dependencies in package.json locally
  npm install 

  #follow instructions in the directory's readme

Step 4:
Enter Twitter dev keys in conf/twitter.conf

Step 5:
Run the app
   
   ./activator run
   
    

## Licence

This software is licensed under the Apache 2 license, quoted below.

Copyright &copy; 2013 **[Matthias Nehlsen](http://www.matthiasnehlsen.com)**.

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this project except in compliance with the License. You may obtain a copy of the License at http://www.apache.org/licenses/LICENSE-2.0.

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.
