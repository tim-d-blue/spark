spark Cookbook
=======================
Install Apache Spark

Usage
-----
```json
    chef.json = {
        "spark" => {
            "git_repository" => "https://github.com/apache/spark.git",
            "git_revision" => "refs/tags/v1.0.1-rc2",
            "username" => "vagrant",
            "group" => "vagrant",
            "home" => "/home/vagrant/spark",
            "master_ip" =>"127.0.0.1",
            "master_port" => "7077",
            "master_webui_port" => "8080",
            "workers" => [ "localhost" ]
        }
    }
```

