<h1>Create VM template and Automate deployment</h1>
This lab has some issue due to the zone. The fisrt check point should be no issue as long as you follow the steps on the lab.
Once you pass the first checkpoint, open cloud shell and enter the following command instead the one the lab provided:

</br>
</br>

```
gcloud compute instances create --zone us-east1-b --source-instance-template vm1-template vm2 vm3 vm4 vm5 vm6 vm7 vm8
```
