---
title: "Roles and permissions" 
sidebar: katalon_studio_docs_sidebar
permalink: katalon-analytics/docs/testops-roles-privileges.html 
description: 
---

In Katalon TestOps, Organization members are assigned different roles with varying permissions and privileges. Those roles are only valid within each Organization.
 
You can find the detailed permissions for each role in the following table:

<table>
	<tbody>
		<tr>
			<td rowspan="2">
				<p><strong>Roles</strong></p>
			</td>
			<td colspan="6">
				<p><strong>Permissions</strong></p>
			</td>
		</tr>
		<tr>
			<td>
				<p><strong>Organization Management</strong></p>
			</td>
			<td>
				<p><strong>Subscription Management</strong></p>
			</td>
			<td>
				<p><strong>User Management</strong></p>
			</td>
			<td>
				<p><strong>License Management</strong></p>
			</td>
			<td>
				<p><strong>License Utilization</strong></p>
			</td>
			<td>
				<p><strong>Usage Dashboard</strong></p>
			</td>
		</tr>
		<tr>
			<td>
				<p><strong>Owner</strong></p>
			</td>
			<td rowspan="2">
				<ul>
					<li>Set Organization Name</li>
					<li>Customize Domain Name</li>
					<li>Enable and configure SSO Settings</li>
					<li>Configure IP Address Restrictions</li>
					<li>Configure Session Timeout</li>
					<li>Enable Katalon Studio Integration for reports upload</li>
					<li>Enable Strict Domain</li>
					<li>Delete Organization</li>
				</ul>
			</td>
			<td>
				<ul>
					<li>Get Quote</li>
					<li>Checkout on Katalon TestOps</li>
				</ul>
			</td>
			<td>
				<ul>
					<li>Invite new users</li>
					<li>Remove users</li>
					<li>Set roles &amp; product access for:&nbsp;</li>
					<ul>
						<li>Admin</li>
						<li>Member</li>
						<li>Billing Manager&nbsp;</li>
					</ul>
					<li>Transfer Organization ownership to another member</li>
				</ul>
			</td>
			<td rowspan="2">
				<ul>
					<li>View subscription information</li>
					<li>Add/remove users from licenses</li>
					<li>View/delete the Online Licenses list</li>
					<li>Create/view/delete the Offline Licenses list</li>
					<li>View/delete the registered machines</li>
				</ul>
			</td>
			<td rowspan="2">
				<ul>
					<li>View license usage</li>
					<li>Filter license usage by users, machineID and license type</li>
					<li>Export license usage under .csv format</li>
				</ul>
			</td>
			<td rowspan="3">
				<ul>
					<li>View TestOps test executions usage</li>
					<li>Export usage dashboard under .csv format</li>
				</ul>
			</td>
		</tr>
		<tr>
			<td>
				<p><strong>Admin</strong></p>
			</td>
			<td>
				<ul>
					<li>Checkout on Katalon TestOpsif there is no predefined Payment Method via Get Quote email</li>
				</ul>
			</td>
			<td>
				<ul>
					<li>Invite new users</li>
					<li>Remove users</li>
					<li>Set roles &amp; product access for:</li>
					<ul>
						<li>Admin</li>
						<li>Member</li>
					</ul>
				</ul>
			</td>
		</tr>
		<tr>
			<td>
				<p><strong>Billing Manager</strong></p>
			</td>
			<td>
				<p>No access</p>
			</td>
			<td>
				<ul>
					<li>Get Quote</li>
					<li>Checkout on Katalon TestOps</li>
					<li>Checkout via Recurly</li>
				</ul>
			</td>
			<td>
				<p>No access</p>
			</td>
			<td>
				<ul>
					<li>View subscription information</li>
				</ul>
			</td>
			<td rowspan="2">
				<p>No access</p>
			</td>
		</tr>
		<tr>
			<td>
				<p><strong>Member</strong></p>
			</td>
			<td>
				<p>No access</p>
			</td>
			<td>
				<p>No access&nbsp;</p>
			</td>
			<td>
				<p>No access</p>
			</td>
			<td>
				<p>No access</p>
			</td>
			<td>
				<p>No access</p>
			</td>
		</tr>
	</tbody>
</table>

> Notes:
>
> If a Member receives a checkout link generated by someone else, they will be able to subscribe and checkout licenses on Katalon TestOps. This is only applicable if there is no predefined Payment Method. See: [Katalon License Subscription](https://docs.katalon.com/katalon-studio/docs/license-subscription.html).

See also: [TestOps User Management](https://docs.katalon.com/katalon-analytics/docs/kt_invite_user_org.html).