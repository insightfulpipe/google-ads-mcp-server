# Google Ads MCP Server by Insightful Pipe

[![MCP Compatible](https://img.shields.io/badge/MCP-Compatible-blue)](https://insightfulpipe.com/mcp-servers/google-ads)
[![Insightful Pipe](https://img.shields.io/badge/Insightful_Pipe-MCP_Servers-purple)](https://insightfulpipe.com/mcp-servers)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

> **The most powerful Google Ads MCP server for AI-powered advertising analytics and campaign management.**

Part of the [Insightful Pipe MCP Server Collection](https://insightfulpipe.com/mcp-servers) — Connect your Google Ads account to Claude, ChatGPT, Cursor, and other AI assistants using the Model Context Protocol (MCP). Analyze campaigns, optimize ad spend, and get AI-driven insights directly in your conversations.

[![Explore All MCP Servers](https://img.shields.io/badge/Explore_All-MCP_Servers-blue?style=for-the-badge)](https://insightfulpipe.com/mcp-servers)

![Google Ads MCP Server](https://insightfulpipe.com/images/google_ads-icon.svg)

## MCP Server URL

```
https://google-ads.insightfulmcp.com/
```

## What is Google Ads MCP?

Google Ads MCP is a **remote Model Context Protocol server** that enables AI assistants to interact with your Google Ads data. This MCP integration allows you to:

- Query campaign performance metrics using natural language
- Analyze ad group and keyword performance
- Get AI-powered recommendations for campaign optimization
- Monitor ROAS, CTR, CPC, and conversion metrics
- Create and manage campaigns, ad groups, and keywords
- Execute custom GAQL queries for advanced reporting

## Installation

### Claude

1. Copy the MCP Server URL: `https://google-ads.insightfulmcp.com/`
2. Open [Claude Connectors Settings](https://claude.ai/settings/connectors)
3. Scroll to the bottom and click **Add custom connector**
4. Paste the URL and click **Add**
5. Click **Connect** on the connector to start authorization
6. Click **Authorize access** in the browser to complete the connection

### ChatGPT

1. Copy the MCP Server URL: `https://google-ads.insightfulmcp.com/`
2. Open ChatGPT Settings → **Connections**
3. Click **Add Connection** and paste the URL
4. Authorize with your InsightfulPipe account

### Claude Code

```bash
claude mcp add google-ads https://google-ads.insightfulmcp.com/
```

### Cursor

1. Open Cursor Settings → **MCP Servers**
2. Add new server with URL: `https://google-ads.insightfulmcp.com/`
3. Authorize the connection

### Gemini CLI

```bash
gemini mcp add --url https://google-ads.insightfulmcp.com/
```

## Available Actions

### Read Actions

| Action | Description |
|--------|-------------|
| `customer` | Customer account information and settings |
| `customer_client` | Customer client hierarchy and management information |
| `customer_client_non_manager` | Customer client non-manager accounts only |
| `label` | Label management and organization data |
| `ad_group_label` | Ad group label associations |
| `campaign_label` | Campaign label associations |
| `customer_label` | Customer label associations |
| `ad_group_criterion_label` | Ad group criterion label associations |
| `ad_group_ad_label` | Ad group ad label associations |
| `audience` | Audience targeting and demographic performance data |
| `user_interest` | User interest categories and availability |
| `campaign_budget` | Campaign budget configuration and recommendations |
| `ad_group_bidding_strategy` | Ad group bidding strategy information |
| `campaign_bidding_strategy` | Campaign bidding strategy configurations |
| `change_status` | Change status history for Google Ads entities |
| `campaign` | Campaign performance data and configuration |
| `ad_group` | Ad group performance data and configuration |
| `ad_group_ad` | Ad creative performance data and policy information |
| `geographic_view` | Geographic and location-based performance data |
| `shopping_performance_view` | Shopping campaign product-level performance data |
| `keyword_view` | Keyword performance data and statistics |
| `display_keyword_view` | Display keyword targeting performance |
| `topic_view` | Topic targeting performance data |
| `user_location_view` | User location-based performance data |
| `click_view` | Click-level performance and location data |
| `generate_keyword_ideas` | Generate keyword ideas from seed keywords or URL using Keyword Planner |
| `gaql` | Execute GAQL (Google Ads Query Language) queries for custom reporting |

### Write Actions

| Action | Description |
|--------|-------------|
| `create_campaign` | Create a new campaign with budget, bidding strategy, and targeting |
| `update_campaign` | Update campaign settings like status, budget, or bidding |
| `create_ad_group` | Create a new ad group within a campaign |
| `update_ad_group` | Update ad group settings like status, bids, or targeting |
| `add_keywords` | Add keywords to an ad group with match types and bids |
| `update_keywords` | Update keyword status, bids, or match types |
| `add_negative_keywords` | Add negative keywords to campaigns or ad groups |
| `create_responsive_search_ad` | Create responsive search ads with multiple headlines and descriptions |
| `upload_click_conversions` | Upload offline click conversions for attribution tracking |
| `upload_customer_list` | Upload customer match lists for audience targeting |
| `remove_customer_list_members` | Remove members from customer match lists |
| `add_location_targeting` | Add geographic location targeting to campaigns |
| `set_device_bid_modifier` | Set bid adjustments for specific device types |

## Usage Examples

### Query Campaign Performance

```
"Show me my Google Ads campaign performance for the last 30 days"
```

### Analyze Keywords

```
"What are my top 10 performing keywords by conversion rate?"
```

### Generate Keyword Ideas

```
"Generate keyword ideas for 'running shoes' using Keyword Planner"
```

### Execute Custom GAQL Query

```
"Run a GAQL query to get campaign metrics grouped by device"
```

### Create Campaign

```
"Create a new search campaign called 'Summer Sale' with a $50 daily budget"
```

### Add Keywords

```
"Add 'best running shoes' as a phrase match keyword to my Running campaign"
```

## Supported Campaign Types

- **Search Campaigns** - Text ads on Google Search
- **Display Campaigns** - Visual ads across the Google Display Network
- **Shopping Campaigns** - Product listing ads
- **Video Campaigns** - YouTube and video partner ads
- **Performance Max** - AI-powered cross-channel campaigns
- **App Campaigns** - Mobile app promotion

## Why Use Google Ads MCP?

### For Marketers
- **Save time** - Query data without logging into Google Ads
- **Natural language** - No need to learn complex reporting interfaces
- **AI insights** - Get recommendations you might have missed

### For Agencies
- **Multi-account management** - Query across client accounts
- **Automated reporting** - Generate client reports conversationally
- **Scalable analysis** - Analyze more data in less time

### For Developers
- **MCP standard** - Built on the open Model Context Protocol
- **Easy integration** - Works with any MCP-compatible AI assistant
- **Full API access** - Both read and write operations supported

## Security & Privacy

- **OAuth 2.0** - Secure authentication with Google
- **Granular permissions** - Control read vs write access
- **Data encryption** - All data transmitted securely
- **SOC 2 compliant** - Enterprise-grade security

## Explore More MCP Servers by Insightful Pipe

Visit **[insightfulpipe.com/mcp-servers](https://insightfulpipe.com/mcp-servers)** to discover our full collection of MCP servers for marketing and analytics.

### Advertising MCP Servers
- [Facebook Ads MCP](https://insightfulpipe.com/mcp-servers/facebook-ads) - Meta advertising analytics
- [TikTok Ads MCP](https://insightfulpipe.com/mcp-servers/tiktok-ads) - TikTok advertising
- [LinkedIn Ads MCP](https://insightfulpipe.com/mcp-servers/linkedin-ads) - B2B advertising
- [Microsoft Ads MCP](https://insightfulpipe.com/mcp-servers/microsoft-ads) - Bing advertising
- [Pinterest Ads MCP](https://insightfulpipe.com/mcp-servers/pinterest-ads) - Pinterest advertising
- [Snapchat Ads MCP](https://insightfulpipe.com/mcp-servers/snapchat-ads) - Snapchat advertising
- [X Ads MCP](https://insightfulpipe.com/mcp-servers/x-ads) - Twitter/X advertising

### Analytics MCP Servers
- [Google Analytics MCP](https://insightfulpipe.com/mcp-servers/google-analytics) - Website analytics
- [Google Search Console MCP](https://insightfulpipe.com/mcp-servers/google-search-console) - SEO analytics

**[View All MCP Servers →](https://insightfulpipe.com/mcp-servers)**

## Resources

- [Documentation](https://insightfulpipe.com/docs/google-ads)
- [Video Tutorial](https://www.youtube.com/playlist?list=PLJNzvjxzI5Xwe__BJJLAelSF0ewO3mEFk)
- [InsightfulPipe Blog](https://insightfulpipe.com/blogs)

## Support

- **Documentation**: [insightfulpipe.com/docs](https://insightfulpipe.com/docs)
- **All MCP Servers**: [insightfulpipe.com/mcp-servers](https://insightfulpipe.com/mcp-servers)
- **Email**: support@insightfulpipe.com

---

**[Insightful Pipe](https://insightfulpipe.com)** — AI-powered marketing analytics through MCP servers. [Explore all integrations →](https://insightfulpipe.com/mcp-servers)

## License

MIT License - see [LICENSE](LICENSE) for details.
