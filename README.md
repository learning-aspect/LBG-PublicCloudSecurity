# LBG-PublicCloudSecurity


https://pnatraj.medium.com/how-to-run-gcloud-command-line-using-a-service-account-f39043d515b9

**************  Rest APIs Security Command Centre  *********************

12416523275109605299
11480643858569817822

https://cloud.google.com/security-command-center/docs/how-to-api-list-findings#filtering_findings

https://cloud.google.com/security-command-center/docs/how-to-api-list-findings

https://xsoar.pan.dev/docs/reference/integrations/google-cloud-scc#known-limitations
Lists an organization or source's findings.

To list across all sources provide a - as the source id. Example: /v1/organizations/{organization_id}/sources/-/findings

HTTP request
GET https://securitycenter.googleapis.com/v1/{parent=organizations/*/sources/*}/findings

https://securitycenter.googleapis.com/v1/organizations/1066590909950/sources/12416523275109605299/findings?severity="MEDIUM"


https://securitycenter.googleapis.com/v1/organizations/1066590909950/sources/12416523275109605299/findings?severity:MEDIUM



*************** params for filters in findings **************************************
KEY filter
VALUE severity="MEDIUM"

KEY pageSize
VALUE 300

KEY filter
VALUE externalUri: "https://console.cloud.google.com/compute/instancesDetail/"

KEY filter
VALUE resource.type="google.compute.Instance"

https://securitycenter.googleapis.com/v1/organizations/1066590909950/sources/12416523275109605299/findings?pageSize=300&filter=externalUri: "https://console.cloud.google.com/compute/instancesDetail/"


KEY fieldMask
VALUE resource.displayName

https://securitycenter.googleapis.com/v1/organizations/1066590909950/sources/12416523275109605299/findings?pageSize=300&filter=externalUri: "https://console.cloud.google.com/compute/instancesDetail/"&fieldMask=resource.displayName

"sourceProperties.Recommendation,sourceProperties.compliance_standards,resource.type,resource.displayName"
***************************************************************************************************

https://securitycenter.googleapis.com/v1/organizations/1066590909950/sources/11480643858569817822/findings

https://securitycenter.googleapis.com/v1/organizations/1066590909950/sources/12416523275109605299/findings

Rest APIs useful links

SecurityRegulatoryCompliance | where ComplianceStandard contains "GCP-CIS-1.1.0"

https://cloud.google.com/security-command-center/docs/how-to-api-list-findings#gcloud

https://cloud.google.com/security-command-center/docs/access-control

https://cloud.google.com/security-command-center/docs/how-to-programmatic-access




//****** Azure Logic Apps
https://docs.microsoft.com/en-us/azure/logic-apps/logic-apps-perform-data-operations

https://docs.microsoft.com/en-us/azure/logic-apps/logic-apps-perform-data-operations#parse-json-action

https://docs.microsoft.com/en-us/azure/logic-apps/logic-apps-http-endpoint

https://docs.microsoft.com/en-us/azure/logic-apps/logic-apps-data-operations-code-samples#create-csv-table-action-example


********************* Azure Log Analytics Rest API *********************************
https://docs.microsoft.com/en-us/rest/api/loganalytics/create-request

https://dev.loganalytics.io/documentation/Using-the-API/RequestFormat

https://docs.microsoft.com/en-us/rest/api/loganalytics/

https://docs.microsoft.com/en-us/azure/azure-monitor/agents/data-sources-custom-logs

https://techcommunity.microsoft.com/t5/azure-monitor/how-to-create-new-table-out-of-existing-table-in-la-workspace/m-p/362550
https://github.com/tsrob50/LogAnalyticsAPIFunction

https://towardsdatascience.com/using-azure-log-analytics-workspaces-to-collect-custom-logs-from-your-vm-99ef7816a0fe
https://docs.microsoft.com/en-us/rest/api/loganalytics/workspace-shared-keys/get-shared-keys



Transforming BigQuery JSON API responses recursively

https://towardsdatascience.com/transforming-bigquery-json-api-responses-recursively-5c462f5b01


********************************* RestAPI Big Query **********************************************

********************* Log Analytical Workspace ************************************
//*** Need to create custom Connector to connect LogicApp to Log Analytical Workspace
{
  "primarySharedKey": "Q2h39oeOHCVdw4ulAFC6f9Wj+HCZ0J4jzcmKbci7OvGwOLg4/yKDwKWYPpAIwSS7qq+I0rd/EKwaDqy9+ZK6XQ==",
  "secondarySharedKey": "hW/xSvkXR6qR/EiKF56nfOiNy3s7bPVbASJ36uFdk3aSLwomo+ilSX/Gy7/Ui2KO/k44s9ERGlcRjcX3B0OGtw=="
}


//json validator

https://www.jsonschema.net/home


//********* Below are BigQuery APIs

https://bigquery.googleapis.com/bigquery/v2/projects/asc-pom/datasets
https://bigquery.googleapis.com/bigquery/v2/projects/asc-pom/datasets/reportingtest/tables/report-test/

https://bigquery.googleapis.com/bigquery/v2/projects/asc-pom/datasets/reportingtest/tables/report-test/data

GET https://www.googleapis.com/bigquery/v2/projects/projectId/jobs/jobId


https://cloud.google.com/bigquery/docs/reference/rest/v2/tables/get

https://cloud.google.com/bigquery/docs/reference/rest/v2/tabledata/list

https://cloud.google.com/bigquery/docs/reference/rest/v2/DataFormatOptions

https://cloud.google.com/bigquery/docs/reference/api-uploads
https://cloud.google.com/bigquery/docs/reference/rest/v2/TableReference

https://cloud.google.com/bigquery/docs/reference/rest/v2/datasets/list


https://cloud.google.com/bigquery/docs/information-schema-tables#bq_2

https://cloud.google.com/bigquery/docs/reference/rest/v2/StandardSqlDataType#standardsqlstructtype


