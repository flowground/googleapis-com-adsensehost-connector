# ![LOGO](logo.png) AdSense Host **flow**ground Connector

## Description

A generated **flow**ground connector for the AdSense Host API (version v4.1).

Generated from: https://api.apis.guru/v2/specs/googleapis.com/adsensehost/v4.1/swagger.json<br/>
Generated at: 2019-05-07T17:41:08+03:00

## API Description

Generates performance reports, generates ad codes, and provides publisher management capabilities for AdSense Hosts.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### List hosted accounts associated with this AdSense account by ad client id.

*Tags:* `accounts`

#### Input Parameters
* `filterAdClientId` - _required_ - Ad clients to list accounts for.
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Get information about the selected associated AdSense account.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_ - Account to get information about.
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### List all hosted ad clients in the specified hosted account.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_ - Account for which to list ad clients.
* `maxResults` - _optional_ - The maximum number of ad clients to include in the response, used for paging.
* `pageToken` - _optional_ - A continuation token, used to page through ad clients. To retrieve the next page, set this parameter to the value of "nextPageToken" from the previous response.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Get information about one of the ad clients in the specified publisher's AdSense account.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_ - Account which contains the ad client.
* `adClientId` - _required_ - Ad client to get.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### List all ad units in the specified publisher's AdSense account.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_ - Account which contains the ad client.
* `adClientId` - _required_ - Ad client for which to list ad units.
* `includeInactive` - _optional_ - Whether to include inactive ad units. Default: true.
* `maxResults` - _optional_ - The maximum number of ad units to include in the response, used for paging.
* `pageToken` - _optional_ - A continuation token, used to page through ad units. To retrieve the next page, set this parameter to the value of "nextPageToken" from the previous response.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Update the supplied ad unit in the specified publisher AdSense account. This method supports patch semantics.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_ - Account which contains the ad client.
* `adClientId` - _required_ - Ad client which contains the ad unit.
* `adUnitId` - _required_ - Ad unit to get.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Insert the supplied ad unit into the specified publisher AdSense account.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_ - Account which will contain the ad unit.
* `adClientId` - _required_ - Ad client into which to insert the ad unit.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Update the supplied ad unit in the specified publisher AdSense account.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_ - Account which contains the ad client.
* `adClientId` - _required_ - Ad client which contains the ad unit.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Delete the specified ad unit from the specified publisher AdSense account.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_ - Account which contains the ad unit.
* `adClientId` - _required_ - Ad client for which to get ad unit.
* `adUnitId` - _required_ - Ad unit to delete.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Get the specified host ad unit in this AdSense account.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_ - Account which contains the ad unit.
* `adClientId` - _required_ - Ad client for which to get ad unit.
* `adUnitId` - _required_ - Ad unit to get.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Get ad code for the specified ad unit, attaching the specified host custom channels.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_ - Account which contains the ad client.
* `adClientId` - _required_ - Ad client with contains the ad unit.
* `adUnitId` - _required_ - Ad unit to get the code for.
* `hostCustomChannelId` - _optional_ - Host custom channel to attach to the ad code.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Generate an AdSense report based on the report request sent in the query parameters. Returns the result as JSON; to retrieve output in CSV format specify "alt=csv" as a query parameter.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_ - Hosted account upon which to report.
* `dimension` - _optional_ - Dimensions to base the report on.
* `endDate` - _required_ - End of the date range to report on in "YYYY-MM-DD" format, inclusive.
* `filter` - _optional_ - Filters to be run on the report.
* `locale` - _optional_ - Optional locale to use for translating report output to a local language. Defaults to "en_US" if not specified.
* `maxResults` - _optional_ - The maximum number of rows of report data to return.
* `metric` - _optional_ - Numeric columns to include in the report.
* `sort` - _optional_ - The name of a dimension or metric to sort the resulting report on, optionally prefixed with "+" to sort ascending or "-" to sort descending. If no prefix is specified, the column is sorted ascending.
* `startDate` - _required_ - Start of the date range to report on in "YYYY-MM-DD" format, inclusive.
* `startIndex` - _optional_ - Index of the first row of report data to return.

### List all host ad clients in this AdSense account.

*Tags:* `adclients`

#### Input Parameters
* `maxResults` - _optional_ - The maximum number of ad clients to include in the response, used for paging.
* `pageToken` - _optional_ - A continuation token, used to page through ad clients. To retrieve the next page, set this parameter to the value of "nextPageToken" from the previous response.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Get information about one of the ad clients in the Host AdSense account.

*Tags:* `adclients`

#### Input Parameters
* `adClientId` - _required_ - Ad client to get.
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### List all host custom channels in this AdSense account.

*Tags:* `customchannels`

#### Input Parameters
* `adClientId` - _required_ - Ad client for which to list custom channels.
* `maxResults` - _optional_ - The maximum number of custom channels to include in the response, used for paging.
* `pageToken` - _optional_ - A continuation token, used to page through custom channels. To retrieve the next page, set this parameter to the value of "nextPageToken" from the previous response.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Update a custom channel in the host AdSense account. This method supports patch semantics.

*Tags:* `customchannels`

#### Input Parameters
* `adClientId` - _required_ - Ad client in which the custom channel will be updated.
* `customChannelId` - _required_ - Custom channel to get.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Add a new custom channel to the host AdSense account.

*Tags:* `customchannels`

#### Input Parameters
* `adClientId` - _required_ - Ad client to which the new custom channel will be added.
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Update a custom channel in the host AdSense account.

*Tags:* `customchannels`

#### Input Parameters
* `adClientId` - _required_ - Ad client in which the custom channel will be updated.
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Delete a specific custom channel from the host AdSense account.

*Tags:* `customchannels`

#### Input Parameters
* `adClientId` - _required_ - Ad client from which to delete the custom channel.
* `customChannelId` - _required_ - Custom channel to delete.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Get a specific custom channel from the host AdSense account.

*Tags:* `customchannels`

#### Input Parameters
* `adClientId` - _required_ - Ad client from which to get the custom channel.
* `customChannelId` - _required_ - Custom channel to get.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### List all host URL channels in the host AdSense account.

*Tags:* `urlchannels`

#### Input Parameters
* `adClientId` - _required_ - Ad client for which to list URL channels.
* `maxResults` - _optional_ - The maximum number of URL channels to include in the response, used for paging.
* `pageToken` - _optional_ - A continuation token, used to page through URL channels. To retrieve the next page, set this parameter to the value of "nextPageToken" from the previous response.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Add a new URL channel to the host AdSense account.

*Tags:* `urlchannels`

#### Input Parameters
* `adClientId` - _required_ - Ad client to which the new URL channel will be added.
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Delete a URL channel from the host AdSense account.

*Tags:* `urlchannels`

#### Input Parameters
* `adClientId` - _required_ - Ad client from which to delete the URL channel.
* `urlChannelId` - _required_ - URL channel to delete.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Create an association session for initiating an association with an AdSense user.

*Tags:* `associationsessions`

#### Input Parameters
* `productCode` - _required_ - Products to associate with the user.
* `userLocale` - _optional_ - The preferred locale of the user.
* `websiteLocale` - _optional_ - The locale of the user's hosted website.
* `websiteUrl` - _required_ - The URL of the user's hosted website.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Verify an association session after the association callback returns from AdSense signup.

*Tags:* `associationsessions`

#### Input Parameters
* `token` - _required_ - The token returned to the association callback URL.
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Generate an AdSense report based on the report request sent in the query parameters. Returns the result as JSON; to retrieve output in CSV format specify "alt=csv" as a query parameter.

*Tags:* `reports`

#### Input Parameters
* `dimension` - _optional_ - Dimensions to base the report on.
* `endDate` - _required_ - End of the date range to report on in "YYYY-MM-DD" format, inclusive.
* `filter` - _optional_ - Filters to be run on the report.
* `locale` - _optional_ - Optional locale to use for translating report output to a local language. Defaults to "en_US" if not specified.
* `maxResults` - _optional_ - The maximum number of rows of report data to return.
* `metric` - _optional_ - Numeric columns to include in the report.
* `sort` - _optional_ - The name of a dimension or metric to sort the resulting report on, optionally prefixed with "+" to sort ascending or "-" to sort descending. If no prefix is specified, the column is sorted ascending.
* `startDate` - _required_ - Start of the date range to report on in "YYYY-MM-DD" format, inclusive.
* `startIndex` - _optional_ - Index of the first row of report data to return.

## License

**flow**ground :- Telekom iPaaS / googleapis-com-adsensehost-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
