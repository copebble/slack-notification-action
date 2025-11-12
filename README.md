# github actions for slack notification

```yaml
- name: "Notification to Slack Channel"
  uses: copebble/slack-notification-action@v1
  if: ${{ success() || failure() }}
```