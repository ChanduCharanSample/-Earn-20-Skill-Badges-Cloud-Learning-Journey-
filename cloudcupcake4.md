# Cloud Speech API 3 Ways: Challenge Lab
Run the following Commands in CloudShell

```
export ZONE=$(gcloud compute instances list lab-vm --format 'csv[no-heading](zone)')
gcloud compute ssh lab-vm --project=$DEVSHELL_PROJECT_ID --zone=$ZONE --quiet

```
Go to Credentials from [here](https://console.cloud.google.com/apis/credentials)

```
export A9PI_KEY=
export task_2_file_name=""
export task_3_request_file=""
export task_3_response_file=""
export task_4_sentence=""
export task_4_file=""
export task_5_sentence=""
export task_5_file=""

```

```
curl -LO https://raw.githubusercontent.com/ChanduCharanSample/-Earn-20-Skill-Badges-Cloud-Learning-Journey-/main/cloudcupcake4.sh
sudo chmod +x cloudcupcake4.sh
./cloudcupcake4.sh


```
Congratulations 🎉 for completing the Lab !
