# ckad-prep

Some Tip:

The CKAD certification is an open book exam(you get access to kubernetes.io & its subdomain). And all question would have their answeres somehwere in the site however the KEY is to manage the time and clear as many questions as possible. 

The key is accuracy with speed. You can not afford to learn the concept during the exam. You need actual hands-on otherwise it would be difficult.

Sample Questions for CKAD

# Use imperative commands only

<code> Create Pod with image=busybox which executes command : 'sleep 3600' </code>

<code> Create a pod with name=busybox-pod, image=buysbox, namespace=ns-pod </code>

<code> Create a deployment with image=buysbox, replicas=3 in default namespace</code>

<code> Create a deployment with name=busybox-deployment, image=buysbox, namespace=ns01 </code>

<code> Create a deployment with name=busybox-deployment, image=buysbox, namespace=ns01 and expose the deployment containerPort: 80 </code>

<code> Create a deployment with name=busybox-deployment, image=buysbox, namespace=ns01 and make it accessible on port 30080 on node</code>

<code> Create a deployment with name=busybox-deployment, image=buysbox, namespace=ns02 </code>

<code> Create a job with name=busybox-job, image=busybox,args : echo date; sleep 10 </code>

<code> Create a job with name=busybox-job, image=busybox,args : echo date; sleep 10 and it should run 10 times with 3 at a time </code>

<code> Create a job with name=busybox-job, image=busybox,args : sleep 30, and make sure kubernets should terminate the job if it runs for more then 25 seconds. </code>

<code> Create a cronjob with name=busybox-cron, image=busybox, command : sleep 30 which runs every 5 minute. </code>


