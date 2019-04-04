# Document History for Amazon EKS<a name="doc-history"></a>

The following table describes the major updates and new features for the Amazon EKS User Guide\. We also update the documentation frequently to address the feedback that you send us\. 

| Change | Description | Date | 
| --- |--- |--- |
| [Amazon EKS Control Plane Logging](https://docs.aws.amazon.com/eks/latest/userguide/control-plane-logs.html) | Amazon EKS control plane logging makes it easy for you to secure and run your clusters by providing audit and diagnostic logs directly from the Amazon EKS control plane to CloudWatch Logs in your account\.  | April 4, 2019 | 
| [Kubernetes Version 1\.12](#doc-history) | Added Kubernetes version 1\.12 support for new clusters and version upgrades\. | March 28, 2019 | 
| [Added App Mesh Getting Started Guide](https://docs.aws.amazon.com/eks/latest/userguide/mesh-gs-k8s.html) | Added documentation for getting started with App Mesh and Kubernetes\. | March 27, 2019 | 
| [Amazon EKS API server endpoint private access](https://docs.aws.amazon.com/eks/latest/userguide/cluster-endpoint.html) | Added documentation for disabling public access for your Amazon EKS cluster's Kubernetes API server endpoint\. | March 19, 2019 | 
| [Added topic for installing the Kubernetes metrics server](https://docs.aws.amazon.com/eks/latest/userguide/metrics-server.html) | The Kubernetes metrics server is an aggregator of resource usage data in your cluster\. | March 18, 2019 | 
| [Added list of related open source projects](https://docs.aws.amazon.com/eks/latest/userguide/metrics-server.html) | These open source projects extend the functionality of Kubernetes clusters running on AWS, including clusters managed by Amazon EKS\. | March 15, 2019 | 
| [Added topic for installing Helm locally](https://docs.aws.amazon.com/eks/latest/userguide/helm.html) | The `helm` package manager for Kubernetes helps you install and manage applications on your Kubernetes cluster\. This topic helps you install and run the `helm` and `tiller` binaries locally so that you can install and manage charts using the `helm` CLI on your local system\. | March 11, 2019 | 
| [Amazon EKS platform version update](https://docs.aws.amazon.com/eks/latest/userguide/platform-versions.html) |  New platform version updating Amazon EKS Kubernetes 1\.11 clusters to patch level 1\.11\.8 to address [CVE\-2019\-1002100](https://discuss.kubernetes.io/t/kubernetes-security-announcement-v1-11-8-1-12-6-1-13-4-released-to-address-medium-severity-cve-2019-1002100/5147)\. | March 8, 2019 | 
| [Increased cluster limit](https://docs.aws.amazon.com/eks/latest/userguide/service_limits.html) | Amazon EKS has increased the number of clusters that you can create in a region from 3 to 50\. | February 13, 2019 | 
| [Amazon EKS region expansion](#doc-history) | Amazon EKS is now available in the EU \(London\) \(`eu-west-2`\), EU \(Paris\) \(`eu-west-3`\), and Asia Pacific \(Mumbai\) \(`ap-south-1`\) regions\. | February 13, 2019 | 
| [New Amazon EKS\-optimized AMI patched for ALAS\-2019\-1156](https://docs.aws.amazon.com/eks/latest/userguide/eks-optimized-ami.html) | Amazon EKS has updated the Amazon EKS\-optimized AMI to address the vulnerability described in [ALAS\-2019\-1156](https://alas.aws.amazon.com/ALAS-2019-1156.html)\. | February 11, 2019 | 
| [New Amazon EKS\-optimized AMI patched for ALAS2\-2019\-1141](https://docs.aws.amazon.com/eks/latest/userguide/eks-optimized-ami.html) | Amazon EKS has updated the Amazon EKS\-optimized AMI to address the CVEs referenced in [ALAS2\-2019\-1141](https://alas.aws.amazon.com/AL2/ALAS-2019-1141.html)\. | January 9, 2019 | 
| [Amazon EKS region expansion](#doc-history) | Amazon EKS is now available in the Asia Pacific \(Seoul\) \(`ap-northeast-2`\) region\. | January 9, 2019 | 
| [Amazon EKS region expansion](#doc-history) | Amazon EKS is now available in the following additional regions: EU \(Frankfurt\) \(`eu-central-1`\), Asia Pacific \(Tokyo\) \(`ap-northeast-1`\), Asia Pacific \(Singapore\) \(`ap-southeast-1`\), and Asia Pacific \(Sydney\) \(`ap-southeast-2`\)\. | December 19, 2018 | 
| [Amazon EKS cluster updates](https://docs.aws.amazon.com/eks/latest/userguide/update-cluster.html) | Added documentation for Amazon EKS [cluster Kubernetes version updates](https://docs.aws.amazon.com/eks/latest/userguide/update-cluster.html) and [worker node replacement](https://docs.aws.amazon.com/eks/latest/userguide/update-workers.html)\. | December 12, 2018 | 
| [Amazon EKS region expansion](#doc-history) | Amazon EKS is now available in the EU \(Stockholm\) \(`eu-north-1`\) region\. | December 11, 2018 | 
| [Amazon EKS platform version update](https://docs.aws.amazon.com/eks/latest/userguide/platform-versions.html) |  New platform version updating Kubernetes to patch level 1\.10\.11 to address [CVE\-2018\-1002105](https://aws.amazon.com/security/security-bulletins/AWS-2018-020/)\. | December 4, 2018 | 
| [Added version 1\.0\.0 support for the Application Load Balancer ingress controller](https://github.com/kubernetes-sigs/aws-alb-ingress-controller) | The Application Load Balancer ingress controller releases version 1\.0\.0 with formal support from AWS\. | November 20, 2018 | 
| [Added support for CNI network configuration](https://docs.aws.amazon.com/eks/latest/userguide/cni-custom-network.html) | The Amazon VPC CNI plugin for Kubernetes version 1\.2\.1 now supports custom network configuration for secondary pod network interfaces\. | October 16, 2018 | 
| [Added support for MutatingAdmissionWebhook and ValidatingAdmissionWebhook](https://docs.aws.amazon.com/eks/latest/userguide/platform-versions.html) | Amazon EKS platform version `1.10-eks.2` now supports `MutatingAdmissionWebhook` and `ValidatingAdmissionWebhook` admission controllers\. | October 10, 2018 | 
| [Added Partner AMI information](https://docs.aws.amazon.com/eks/latest/userguide/eks-partner-amis.html) | Canonical has partnered with Amazon EKS to create worker node AMIs that you can use in your clusters\. | October 3, 2018 | 
| [Added instructions for AWS CLI update\-kubeconfig command](https://docs.aws.amazon.com/eks/latest/userguide/create-kubeconfig.html) | Amazon EKS has added the `update-kubeconfig` to the AWS CLI to simplify the process of creating a `kubeconfig` file for accessing your cluster\. | September 21, 2018 | 
| [New Amazon EKS\-optimized AMIs](https://docs.aws.amazon.com/eks/latest/userguide/eks-optimized-ami.html) | Amazon EKS has updated the Amazon EKS\-optimized AMIs \(with and without GPU support\) to provide various security fixes and AMI optimizations\. | September 13, 2018 | 
| [Amazon EKS region expansion](#doc-history) | Amazon EKS is now available in the EU \(Ireland\) \(`eu-west-1`\) region\. | September 5, 2018 | 
| [Amazon EKS platform version update](https://docs.aws.amazon.com/eks/latest/userguide/platform-versions.html) |  New platform version with support for Kubernetes [aggregation layer](https://kubernetes.io/docs/concepts/extend-kubernetes/api-extension/apiserver-aggregation/) and the [Horizontal Pod Autoscaler](https://kubernetes.io/docs/tasks/run-application/horizontal-pod-autoscale/)\(HPA\)\. | August 31, 2018 | 
| [New Amazon EKS\-optimized AMIs and GPU support](https://docs.aws.amazon.com/eks/latest/userguide/eks-optimized-ami.html) | Amazon EKS has updated the Amazon EKS\-optimized AMI to use a new AWS CloudFormation worker node template and [bootstrap script](https://github.com/awslabs/amazon-eks-ami/blob/master/files/bootstrap.sh)\. In addition, a new [Amazon EKS\-optimized AMI with GPU support](gpu-ami.html) is available\. | August 22, 2018 | 
| [New Amazon EKS\-optimized AMI patched for ALAS2\-2018\-1058](https://docs.aws.amazon.com/eks/latest/userguide/eks-optimized-ami.html) | Amazon EKS has updated the Amazon EKS\-optimized AMI to address the CVEs referenced in [ALAS2\-2018\-1058](https://alas.aws.amazon.com/AL2/ALAS-2018-1058.html)\. | August 14, 2018 | 
| [Amazon EKS\-optimized AMI build scripts](https://docs.aws.amazon.com/eks/latest/userguide/eks-optimized-ami.html) | Amazon EKS has open\-sourced the build scripts that are used to build the Amazon EKS\-optimized AMI\. These build scripts are now available on GitHub\.  | July 10, 2018 | 
| [Amazon EKS initial release](#doc-history) | Initial documentation for service launch | June 5, 2018 | 