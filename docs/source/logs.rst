Latest Logs From Latest Build
==============================

Generated On: 2024-12-05 19:05:46 UTC

These are the latest logs generated from your latest build.  

.. tip:: 
   Complete logs from all builds can be found `here on GitHub <https://github.com/AnkurPokhrel8/raspberryCYT180/blob/main/tml-airflow/logs/logs.txt>`_

.. code-block:: 
  :linenos:

  [INFO 2024-12-05_19:03:26] STEP 1: completed - TML system parameters successfully gathered

  [INFO 2024-12-05_19:03:33] STEP 2: Create topics started

  [INFO 2024-12-05_19:03:59] STEP 2: Completed

  [INFO 2024-12-05_19:04:11] STEP 3: producing data started

  [INFO 2024-12-05_19:04:16] MQTT connection established...

  [INFO 2024-12-05_19:04:17] STEP 4: Preprocessing started

  [INFO 2024-12-05_19:04:21] STEP 4: Preprocessing started

  [INFO 2024-12-05_19:04:23] STEP 7: Visualization started

  [INFO 2024-12-05_19:04:30] STEP 7: /Viperviz/viperviz-linux-amd64 0.0.0.0 9005

  [INFO 2024-12-05_19:04:49] STEP 8: Starting docker push for: pokhrelankur8@gmail.com/myprivategpt-71b9-amd64

  [INFO 2024-12-05_19:04:57] STEP 9: Success starting Qdrant.  Here is the run command: docker run -d -p 6333:6333 -v $(pwd)/qdrant_storage:/qdrant/storage:z qdrant/qdrant

  [INFO 2024-12-05_19:05:02] STEP 9: Starting privateGPT

  [WARN 2024-12-05_19:05:09] STEP 8: There seems to be an issue creating the container.  Here is the commit command: docker commit a3471302795b pokhrelankur8@gmail.com/myprivategpt-71b9-amd64 - message=1.  Container may NOT pushed.

  [INFO 2024-12-05_19:05:26] STEP 9: Success starting privateGPT.  Here is the run command: docker run -d -p 8001:8001 --net=host --env PORT=8001 --env GPU=0 --env COLLECTION=tml --env WEB_CONCURRENCY=1 --env CUDA_VISIBLE_DEVICES=0 maadsdocker/tml-privategpt-no-gpu-amd64

  [WARN 2024-12-05_19:05:29] STEP 8: There may be an issue pushing to Docker Hub, or just wait few seconds to see if the container shows up.  Here is the command: docker push pokhrelankur8@gmail.com/myprivategpt-71b9-amd64 - message=1

  [INFO 2024-12-05_19:05:45] STEP 10: Started to build the documentation

  [INFO 2024-12-05_19:05:48] STEP 10: Documentation successfully built on GitHub..Readthedocs build in process and should complete in few seconds


