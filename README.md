# Google Ads UTM Tracking Template Repository

This repository provides a Google Ads tracking template that can be used in the "Campaign URL options" section to track campaign performance with UTM parameters.

## UTM Tracking Template

```
{lpurl}?utm_source=google&utm_medium=cpc&utm_campaign={campaignid}&utm_term={keyword}&utm_content={adgroupid}&utm_id={creative}&matchtype={matchtype}&network={network}&device={device}&targetid={targetid}
```

## How to Implement

1. **Go to your Google Ads account.**
2. **Navigate to Campaigns** and select the campaign you want to apply the tracking template to.
3. **Click on "Settings"** and scroll down to the "Campaign URL options" section.
4. **Paste the tracking template** (above) into the "Tracking template" field.
5. **Save the changes.**

## Explanation of Parameters

| Parameter       | Description |
|----------------|-------------|
| `{lpurl}`      | Landing page URL |
| `utm_source=google` | Identifies the traffic source as Google |
| `utm_medium=cpc` | Specifies the traffic type as cost-per-click |
| `utm_campaign={campaignid}` | Dynamically inserts the campaign ID |
| `utm_term={keyword}` | Captures the keyword triggering the ad |
| `utm_content={adgroupid}` | Inserts the ad group ID |
| `utm_id={creative}` | Captures the unique creative ID |
| `matchtype={matchtype}` | Indicates the match type of the keyword |
| `network={network}` | Specifies whether the ad appeared on search or display network |
| `device={device}` | Identifies the user’s device type |
| `targetid={targetid}` | Provides the targeting criteria ID |

## Additional Notes

- Ensure auto-tagging is enabled in Google Ads to track performance in Google Analytics.
- You can customize the UTM parameters based on your tracking needs.
- This tracking template helps analyze ad performance across different campaigns, ad groups, and creatives.

## Contributing

Feel free to contribute by submitting a pull request or opening an issue!
