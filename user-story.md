
# User Story

As a user, I want to personalize the WeChat Mini Program invitation so that I can engage experts in a more personalized and culturally relevant manner. This will improve the user experience and make it more likely that the experts will accept the invitation.

## Acceptance Criteria

1. When I send an invitation to a network member, the system should check if a localized name is available for that member. If a localized name is available, the system should generate an invitation using the following template:

```
[LOCALIZED NAME] 您好！

GLG格理集团邀您关注GLG微信专家平台以方便接收项目和沟通后续进展。请点击链接扫描二维码关注:
https://messaging.glginc.cn/mcm-invite/?token={{MP_TOKEN}}。感谢您的支持！
```
Example: (https://streamliner.glgresearch.com/prism/member/6487737)
```
杨予 您好！

GLG格理集团邀您关注GLG微信专家平台以方便接收项目和沟通后续进展。请点击链接扫描二维码关注:
https://messaging.glginc.cn/mcm-invite/?token={{MP_TOKEN}}。感谢您的支持！
```
2. If a localized name is not available, the system should generate an invitation using the following template:

```
[SURNAME] [FIRST NAME] - Chen Lishen 您好！ 

GLG格理集团邀您关注GLG微信专家平台以方便接收项目和沟通后续进展。请点击链接扫描二维码关注:
https://messaging.glginc.cn/mcm-invite/?token={{MP_TOKEN}}。感谢您的支持！
```
Example:
```
Musgrave Lily 您好！ 

GLG格理集团邀您关注GLG微信专家平台以方便接收项目和沟通后续进展。请点击链接扫描二维码关注:
https://messaging.glginc.cn/mcm-invite/?token={{MP_TOKEN}}。感谢您的支持！
```