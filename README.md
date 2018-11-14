# plunifycloud_tutorial
## Overview
This is a simple tutorial for user to use Plunify Cloud service through InTIme software. This tutorial covers the  Hot Start recipe, InTIme Default recipe, Extra Optimization recipe. The order of recipe and their configurations are shown as below.

Recipe 1 : Hotstart
  - runs per round  : 2
  - rounds          : 1
  - concurrent runs : 2
  
Recipe 2 : InTime Default
  - runs per round  : 2
  - rounds          : 1
  - concurrent runs : 2

Recipe 3 : Extra Optimization Exploration
  - runs per round  : 2
  - rounds          : 1
  - concurrent runs : 2

## Requirements
1. Intime software
2. Vivado 2017.2
3. Plunify Cloud account with at 100 credits

## Steps

1. CLone the sample project .
2. Start Intime and open the project .
3. Select the targeted toolchain. 
4. Change the 'Run Target' option to 'Plunify Cloud'.
5. Change 'Recipe' option to 'Hot Start'.
6. Configure the other flow properties as shown below. 
7. Click 'Start Recipe' to submit the job to Plunify Cloud.
8. Enter your credential. Note you only need to do this once.
9. Select the class of machine to use for cloud. Use Class 1 machine for this sample project. 
10. After the class of machine is chosen, Intime will create a job ID for this submission and upload the project into Plunify Cloud for compilation. A notification will be shown if the job submission is successful. Record the remote job ID ( 81181 for this example ). You may use this job ID to track the job status in Plunify Cloud website.
11. In the Plunify Cloud web console, check the job status under 'History'>'Usage History'
12. Upon completion, a notification email will be sent into your inbox.
13. Back to Intime software, right click 'impl 1' revision and select 'Job Action'>'Download Remote Results'>'Download Remote Results Without Project File' to download the results into Intime. 
14. Selects the revision which has the best TNS slack as custom parent revision. 
