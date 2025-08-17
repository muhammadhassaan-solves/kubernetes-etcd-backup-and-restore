<h1>Kubernetes Etcd Backup and Restore</h1>


<h2>Description</h2>
This project demonstrates how to protect and restore the critical state of a Kubernetes cluster by managing etcd backups. It covers creating test resources, taking snapshots, simulating failures, and restoring the system to full operation. It emphasizes strategies for disaster recovery, ensuring minimal downtime, and maintaining operational resilience for enterprise-grade applications.
<br />


<h2>Tools and Technologies</h2>

<ul>
    <li>Kubernetes (kubeadm)</li>
    <li>etcd</li>
    <li>etcdctl</li>
    <li>Ubuntu 24.04 LTS</li>
    <li>Bash / Linux CLI</li>
</ul>

<h2>Project Walk-through</h2>

<p align="center">
Configure etcdctl <br />
<img src="https://i.postimg.cc/zvtddGtn/1.jpg"/>
<br />
<br />
Create Sample Resources for Testing <br/>
<img src="https://i.postimg.cc/Hs84GzVG/2.jpg" />
<br />
<br />
Perform Etcd Snapshot Backup <br/>
<img src="https://i.postimg.cc/8c2vP8s2/3.jpg"/>
<br />
<br />
Simulate Cluster Failure & Restore from Etcd Snapshot <br/>
<img src="https://i.postimg.cc/RCybyXvf/d.jpg" />
<br />
<br />
Verify Restored Resources & Test Application Functionality <br/>
<img src="https://i.postimg.cc/Hnw5SYp6/e.jpg" />
<br />
<br />


</p>

