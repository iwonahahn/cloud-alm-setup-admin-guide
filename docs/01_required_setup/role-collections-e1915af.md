<!-- loioe1915af019da48cc8b8e58399e8ea235 -->

# Role Collections

Roles in SAP Cloud ALM are delivered as predefined collections. You don't have to configure any role collections yourself. Instead, you can simply assign the relevant role collections to the users based on their tasks and requirements.

> ### Caution:  
> The *Cross Global Administrator* and the *User & Access Management Administrator* role collections consist of more than one role template.
> 
> If you want to create your own role collections by bundling several predefined role collections together, don't forget to add the role template `FlexOperator` whenever you include the role templates `x_calm_GlobalAdministrator` or `x_uam_UserAdministrator`.

The following role collections are available for each application area in SAP Cloud ALM:


<table>
<tr>
<th valign="top">

Application Area



</th>
<th valign="top">

Role Title



</th>
<th valign="top">

Description



</th>
<th valign="top">

Role Name



</th>
<th valign="top">

Role Template



</th>
</tr>
<tr>
<td valign="top" rowspan="2">

Cross



</td>
<td valign="top">

Global Administrator



</td>
<td valign="top">

Create and manage all SAP Cloud ALM objects, except personal or sensitive data

> ### Caution:  
> This role provides the complete set of authorizations. We recommend configuring suitable roles for your users.



</td>
<td valign="top">

Cross Global Administrator



</td>
<td valign="top">

`x_calm_GlobalAdministrator`

`FlexOperator`



</td>
</tr>
<tr>
<td valign="top">

Global Auditor



</td>
<td valign="top">

View all SAP Cloud ALM objects, except personal or sensitive data

This role is to be used for general audit purposes.



</td>
<td valign="top">

Cross Global Auditor



</td>
<td valign="top">

 `x_calm_GlobalAuditor` 



</td>
</tr>
<tr>
<td valign="top" rowspan="2">

User & Access Management



</td>
<td valign="top">

User Administrator



</td>
<td valign="top">

Create and manage users, assign and approve authorizations



</td>
<td valign="top">

User & Access Management Administrator



</td>
<td valign="top">

`x_uam_UserAdministrator`

`FlexOperator`



</td>
</tr>
<tr>
<td valign="top">

User Viewer



</td>
<td valign="top">

View users and authorization assignments



</td>
<td valign="top">

User & Access Management Viewer



</td>
<td valign="top">

 `x_uam_UserViewer` 



</td>
</tr>
<tr>
<td valign="top" rowspan="4">

Project & Task Management

Process Management

Change & Deployment Management

Test Management



</td>
<td valign="top">

Project Administrator



</td>
<td valign="top">

Edit projects and all associated tasks, scopes, requirements, notes, test cases, and the landscape



</td>
<td valign="top">

Project & Task Management Administrator



</td>
<td valign="top">

 `imp_pjm_ProjectAdministrator` 



</td>
</tr>
<tr>
<td valign="top">

Project Lead



</td>
<td valign="top">

Edit projects and all associated tasks, scopes, requirements, notes, and test cases. View the landscape



</td>
<td valign="top">

Project & Task Management Project Lead



</td>
<td valign="top">

 `imp_pjm_ProjectLead` 



</td>
</tr>
<tr>
<td valign="top">

Project Member



</td>
<td valign="top">

View projects and the landscape. Edit all associated tasks, scopes, requirements, notes, and test cases



</td>
<td valign="top">

Project & Task Management Project Member



</td>
<td valign="top">

 `imp_pjm_ProjectMember` 



</td>
</tr>
<tr>
<td valign="top">

Project Viewer



</td>
<td valign="top">

View projects and all associated tasks, scopes, requirements, notes, test cases, and the landscape



</td>
<td valign="top">

Project & Task Management Project Viewer



</td>
<td valign="top">

 `imp_pjm_ProjectViewer` 



</td>
</tr>
<tr>
<td valign="top" rowspan="5">

Business Process Monitoring



</td>
<td valign="top">

Process Monitoring Administrator



</td>
<td valign="top">

Maintain global and specific configurations, consume KPIs and the respective process content, and process alerts



</td>
<td valign="top">

Business Process Monitoring Administrator



</td>
<td valign="top">

 `ops_bm_ProcessMonitoringAdministrator` 



</td>
</tr>
<tr>
<td valign="top">

Process Manager



</td>
<td valign="top">

Consume KPIs and the respective process content, process alerts, and maintain specific configurations



</td>
<td valign="top">

Business Process Monitoring Process Manager



</td>
<td valign="top">

 `ops_bm_ProcessManager` 



</td>
</tr>
<tr>
<td valign="top">

Process Executor



</td>
<td valign="top">

Consume KPIs and the respective process content, and process alerts



</td>
<td valign="top">

Business Process Monitoring Process Executor



</td>
<td valign="top">

 `ops_bm_ProcessExecutor` 



</td>
</tr>
<tr>
<td valign="top">

Process Monitoring Consumer



</td>
<td valign="top">

Consume KPIs and the respective process content, and view alerts



</td>
<td valign="top">

Business Process Monitoring Consumer



</td>
<td valign="top">

 `ops_bm_ProcessMonitoringConsumer` 



</td>
</tr>
<tr>
<td valign="top">

Process Monitoring Viewer



</td>
<td valign="top">

Consume KPIs and non-sensitive process content, without access to alert information



</td>
<td valign="top">

Business Process Monitoring Viewer



</td>
<td valign="top">

 `ops_bm_ProcessMonitoringViewer` 



</td>
</tr>
<tr>
<td valign="top" rowspan="3">

Integration & Exception Monitoring



</td>
<td valign="top">

Integration Architect



</td>
<td valign="top">

Configure integration monitoring



</td>
<td valign="top">

Integration Monitoring Integration Architect



</td>
<td valign="top">

 `ops_im_IntegrationArchitect` 



</td>
</tr>
<tr>
<td valign="top">

Integration Owner



</td>
<td valign="top">

View the messages in integration monitoring



</td>
<td valign="top">

Integration Monitoring Integration Owner



</td>
<td valign="top">

 `ops_im_IntegrationOwner` 



</td>
</tr>
<tr>
<td valign="top">

Integration Owner Sensitive



</td>
<td valign="top">

View the messages in integration monitoring, including data defined as sensitive



</td>
<td valign="top">

Integration Monitoring Integration Owner Sensitive



</td>
<td valign="top">

 `ops_im_IntegrationOwnerSensitive` 



</td>
</tr>
<tr>
<td valign="top" rowspan="2">

Job & Automation Monitoring



</td>
<td valign="top">

Job Monitoring Administrator



</td>
<td valign="top">

Create, edit, delete, and manage configuration settings, including the display of monitoring data



</td>
<td valign="top">

Job Monitoring Administrator



</td>
<td valign="top">

 `ops_jm_JobMonitoringAdministrator` 



</td>
</tr>
<tr>
<td valign="top">

Job Monitoring Consumer



</td>
<td valign="top">

View the job monitoring application for the maintained global configurations



</td>
<td valign="top">

Job Monitoring Consumer



</td>
<td valign="top">

 `ops_jm_JobMonitoringConsumer` 



</td>
</tr>
<tr>
<td valign="top" rowspan="3">

Real User Monitoring



</td>
<td valign="top">

Real User Analyst Administrator



</td>
<td valign="top">

View utilization and performance of requests, including sensitive data like the user ID, and configure the real user monitoring app



</td>
<td valign="top">

Real User Monitoring Analyst Administrator



</td>
<td valign="top">

 `ops_rum_RealUserAnalystAdministrator` 



</td>
</tr>
<tr>
<td valign="top">

Real User Analyst



</td>
<td valign="top">

View utilization and performance of requests



</td>
<td valign="top">

Real User Monitoring Analyst



</td>
<td valign="top">

 `ops_rum_RealUserAnalyst` 



</td>
</tr>
<tr>
<td valign="top">

Real User Analyst Sensitive



</td>
<td valign="top">

View utilization and performance of requests, including sensitive data like the user ID



</td>
<td valign="top">

Real User Monitoring Analyst Sensitive



</td>
<td valign="top">

 `ops_rum_RealUserAnalystSensitive` 



</td>
</tr>
<tr>
<td valign="top" rowspan="2">

Health Monitoring



</td>
<td valign="top">

Health Monitoring Administrator



</td>
<td valign="top">

Create, edit, delete, and manage configuration settings, including the display of monitoring data



</td>
<td valign="top">

Health Monitoring Administrator



</td>
<td valign="top">

 `ops_hm_HealthMonitoringAdministrator` 



</td>
</tr>
<tr>
<td valign="top">

Health Monitoring Viewer



</td>
<td valign="top">

View health overview and metrics of cloud services



</td>
<td valign="top">

Health Monitoring Viewer



</td>
<td valign="top">

 `ops_hm_HealthMonitoringViewer` 



</td>
</tr>
<tr>
<td valign="top" rowspan="2">

Business Service Management



</td>
<td valign="top">

Business Service Management Administrator



</td>
<td valign="top">

Create and manage business services, and plan events



</td>
<td valign="top">

Business Service Management Administrator



</td>
<td valign="top">

 `ops_bsm_BusinessServiceManagementAdministrator` 



</td>
</tr>
<tr>
<td valign="top">

Business Service Management Viewer



</td>
<td valign="top">

View business services, their configuration, and the event calendar



</td>
<td valign="top">

Business Service Management Viewer



</td>
<td valign="top">

 `ops_bsm_BusinessServiceManagementViewer` 



</td>
</tr>
<tr>
<td valign="top" rowspan="3">

Service Collaboration



</td>
<td valign="top">

Services Administrator



</td>
<td valign="top">

Execute service-specific administration tasks, configure and execute services, and view service execution results



</td>
<td valign="top">

Service Collaboration Administrator



</td>
<td valign="top">

 `sdc_sc_ServicesAdministrator` 



</td>
</tr>
<tr>
<td valign="top">

Services Expert



</td>
<td valign="top">

Configure and execute services, and view own and shared service execution results



</td>
<td valign="top">

Service Collaboration Expert



</td>
<td valign="top">

 `sdc_sc_ServicesExpert` 



</td>
</tr>
<tr>
<td valign="top">

Services Viewer



</td>
<td valign="top">

Browse through the service explorer and view the shared service execution results



</td>
<td valign="top">

Service Collaboration Viewer



</td>
<td valign="top">

 `sdc_sc_ServicesViewer` 



</td>
</tr>
</table>

