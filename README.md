# ckad-prep

Some Tip:

The CKAD certification is an open book exam(you get access to kubernetes.io & its subdomain). And all question would have their answeres somehwere in the site however the KEY is to manage the time and clear as many questions as possible. 

# The key is accuracy with speed. 

You can not afford to learn the concept during the exam. You need actual hands-on otherwise it would be difficult.

Sample Questions for CKAD

You must be very fluent in using imperative commands when working on kubernetes. 
Following are few samples which you should be able to do with use of imperative commands only.

# NOTE : Use imperative commands only

<code> Create Pod with image=busybox which executes command : 'sleep 3600' </code>

<code> Create Pod with image=busybox which executes command : 'sleep 3600' with label: "duration=onehr" </code>

<code> Create a pod with name=busybox-pod, image=buysbox, namespace=ns-pod </code>

<code> Create a deployment with image=buysbox, replicas=3 in default namespace</code>

<code> Create a deployment with name=busybox-deployment, image=buysbox, namespace=ns01 </code>

<code> Create a deployment with name=busybox-deployment, image=buysbox, expose the deployment containerPort: 80 </code>

<code> Create a deployment with name=busybox-deployment, image=buysbox, make it accessible on port 30080 on node</code>

<code> Create a deployment with name=busybox-deployment, image=buysbox, namespace=ns02 </code>

<code> Create a job with name=busybox-job, image=busybox,args : echo date; sleep 10 </code>

<code> Create a job with name=busybox-job, image=busybox,args : echo date; sleep 10 and it should run 10 times with 3 at a time </code>

<code> Create a job with name=busybox-job, image=busybox,args : sleep 30, and job should be terminated if it runs for more then 25 seconds. </code>

<code> Create a cronjob with name=busybox-cron, image=busybox, command : sleep 30 which runs every 5 minute. </code>

<code> 
  
       1. Create deployment with name=busybox-deploy, image=busybox 
  
       2. Once the pod is up & running, change the image of the deployment to my-busybox.
  <code>

# Pod & Lables

## Label the existing pod.

<code> Apply the label "img=busybox" to the busybox-pod </code>

<code> Override the label "img" with the value "busybox-container" to the busybox-pod </code>

<code> Remove the label "img" from the busybox-pod</code>

# Service and Networking
<code> Create pod with busybox image and and expose it 
