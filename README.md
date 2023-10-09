# Notify Slack

A Github Action that allows you to easily notify Slack of the results of a build.

## Usage

```yaml
- name: Slack
  uses: bottlerocketstudios/notify-slack-action@v1
  with:
    webhook_url: ${{ $secrets.SLACK_WEBHOOK_URL }}
    success: true
    artifacts_url: https://www.apple.com
```

## Additional Arguments

There are a number of additional, optional arguments that can be provided to more closely control the transferred artifacts and their destination. See [action.yml](action.yml) for more information.
