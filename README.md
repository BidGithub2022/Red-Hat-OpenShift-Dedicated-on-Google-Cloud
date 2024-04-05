# Red-Hat-OpenShift-Dedicated-on-Google-Cloud

You have logged into your Google Cloud Console.
 
Steps to install OpenShift Dedicated on Google Cloud:
1. Create a project.
2. Enable APIs.
3. Create Service account.
4. Grant roles to the service account.
5. Create a service account key.
6. Adjust Quota.
7. Deploy OpenShift.

## Cluster installation

![Screenshot 2024-04-04 at 11 52 32 AM](https://github.com/BidGithub2022/Red-Hat-OpenShift-Dedicated-on-Google-Cloud/assets/113651761/e539fc8b-e55d-4f6d-b76d-1b652cbee9f1)

![Screenshot 2024-04-04 at 11 53 04 AM](https://github.com/BidGithub2022/Red-Hat-OpenShift-Dedicated-on-Google-Cloud/assets/113651761/82cd8a36-3ae8-4200-be92-17d9cedc3d72)

![Screenshot 2024-04-04 at 11 55 05 AM](https://github.com/BidGithub2022/Red-Hat-OpenShift-Dedicated-on-Google-Cloud/assets/113651761/5a479e53-2b62-4dfa-9a4a-dc4549542d48)

![Screenshot 2024-04-04 at 11 55 46 AM](https://github.com/BidGithub2022/Red-Hat-OpenShift-Dedicated-on-Google-Cloud/assets/113651761/3820ec3d-d396-474a-8646-59791b17e095)

![Screenshot 2024-04-04 at 11 57 49 AM](https://github.com/BidGithub2022/Red-Hat-OpenShift-Dedicated-on-Google-Cloud/assets/113651761/b46d59de-f569-4aa1-b8e1-8e2976363490)

![Screenshot 2024-04-04 at 12 01 39 PM](https://github.com/BidGithub2022/Red-Hat-OpenShift-Dedicated-on-Google-Cloud/assets/113651761/b431b927-0132-4476-90b3-32a1472a3cbf)

![Screenshot 2024-04-04 at 12 03 46 PM](https://github.com/BidGithub2022/Red-Hat-OpenShift-Dedicated-on-Google-Cloud/assets/113651761/349bb5c3-3295-4a4d-8294-7be64e5506e2)

![Screenshot 2024-04-04 at 12 06 14 PM](https://github.com/BidGithub2022/Red-Hat-OpenShift-Dedicated-on-Google-Cloud/assets/113651761/ad506782-0306-4fbe-9ea8-eacde59dc0ef)

![Screenshot 2024-04-04 at 12 06 55 PM](https://github.com/BidGithub2022/Red-Hat-OpenShift-Dedicated-on-Google-Cloud/assets/113651761/f9c50305-bf58-4bae-8162-56737b960ddd)

![Screenshot 2024-04-04 at 12 10 37 PM](https://github.com/BidGithub2022/Red-Hat-OpenShift-Dedicated-on-Google-Cloud/assets/113651761/c4fd05e2-c172-4391-9422-cffb21b38faa)

![Screenshot 2024-04-04 at 12 10 51 PM](https://github.com/BidGithub2022/Red-Hat-OpenShift-Dedicated-on-Google-Cloud/assets/113651761/2092a5a7-8832-495e-842c-77b5f349354c)

Got some error due to some APIs were not anabled. Make sure to go through the doc  to enable respective APIs. "networksecurity" API is missing in the documentation.

## Cluster is ready

![Screenshot 2024-04-04 at 12 53 41 PM](https://github.com/BidGithub2022/Red-Hat-OpenShift-Dedicated-on-Google-Cloud/assets/113651761/769dc986-39e3-41db-84cf-0931fb9f0a77)

## Install the OCV virt operator

![Screenshot 2024-04-04 at 1 12 41 PM](https://github.com/BidGithub2022/Red-Hat-OpenShift-Dedicated-on-Google-Cloud/assets/113651761/37214ea7-d152-4193-8b49-4450fa42e368)

![Screenshot 2024-04-04 at 1 13 00 PM](https://github.com/BidGithub2022/Red-Hat-OpenShift-Dedicated-on-Google-Cloud/assets/113651761/ed7cac50-a717-408e-9348-367abc974a12)

![Screenshot 2024-04-04 at 1 15 10 PM](https://github.com/BidGithub2022/Red-Hat-OpenShift-Dedicated-on-Google-Cloud/assets/113651761/d4aeaa2c-2aec-4beb-aac0-c8e1d70a97e9)

![Screenshot 2024-04-04 at 1 19 09 PM](https://github.com/BidGithub2022/Red-Hat-OpenShift-Dedicated-on-Google-Cloud/assets/113651761/bb6174f9-c435-4f88-825a-97fec143f2d8)

## Create project

![Screenshot 2024-04-04 at 1 21 37 PM](https://github.com/BidGithub2022/Red-Hat-OpenShift-Dedicated-on-Google-Cloud/assets/113651761/6d00cbf2-b0c0-4f9a-9fe8-0ddbbf663b4e)

## Create RHEL 9 VM

![Screenshot 2024-04-04 at 1 22 20 PM](https://github.com/BidGithub2022/Red-Hat-OpenShift-Dedicated-on-Google-Cloud/assets/113651761/b3f33531-e1fe-433c-a5bb-59cc806fcb1a)

![Screenshot 2024-04-04 at 1 22 43 PM](https://github.com/BidGithub2022/Red-Hat-OpenShift-Dedicated-on-Google-Cloud/assets/113651761/4d1549d0-36fa-4350-b5aa-15c5aa6630df)

## Getting error while creating VM

![Screenshot 2024-04-04 at 6 47 50 PM](https://github.com/BidGithub2022/Red-Hat-OpenShift-Dedicated-on-Google-Cloud/assets/113651761/d9a85d39-5111-4d30-ae8a-9e55480c22d8)

![Screenshot 2024-04-04 at 6 48 15 PM](https://github.com/BidGithub2022/Red-Hat-OpenShift-Dedicated-on-Google-Cloud/assets/113651761/7ce9b39d-5627-427b-8038-b4fdca806068)

![Screenshot 2024-04-04 at 6 48 35 PM](https://github.com/BidGithub2022/Red-Hat-OpenShift-Dedicated-on-Google-Cloud/assets/113651761/0f0a36ca-2b28-46b6-8b00-a322428593de)






















# Links to refer:
https://www.youtube.com/watch?v=AI4WwSZJi9g

https://docs.openshift.com/container-platform/4.15/installing/installing_gcp/installing-gcp-account.html

