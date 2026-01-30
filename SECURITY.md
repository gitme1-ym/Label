# Security Policy
script:
  - pipe: atlassian/trigger-pipeline:5.10.1
    variables:
      REPOSITORY: '<string>'
      # ATLASSIAN_ACCOUNT_EMAIL: '<string>' # Optional
      # ATLASSIAN_API_TOKEN: '<string>' # Optional
      # BITBUCKET_ACCESS_TOKEN: '<string>' # Optional
      # ACCOUNT: '<string>' # Optional
      # REF_TYPE: '<string>' # Optional
      # REF_NAME: '<string>' # Optional
      # COMMIT: '<string>' # Optional
      # CUSTOM_PIPELINE_NAME: '<string>' # Optional
      # PIPELINE_VARIABLES: '<json>' # Optional
      # WAIT: '<boolean>' # Optional
      # WAIT_MAX_TIMEOUT: '<integer>' # Optional
      # REQUEST_READ_TIMEOUT: '<integer>' # Optional
      # MAX_RETRIES_ON_FAILURE: '<integer>' # Optional
      # DEBUG: '<boolean>' # Optional
## Supported Versions

Use this section to tell people about which versions of your project are
currently being supported with security updates.

| Version | Supported          |
| ------- | ------------------ |
| 5.1.x   | :white_check_mark: |
| 5.0.x   | :x:                |
| 4.0.x   | :white_check_mark: |
| < 4.0   | :x:                |

## Reporting a Vulnerability

Use this section to tell people how to report a vulnerability.

Tell them where to go, how often they can expect to get an update on a
reported vulnerability, what to expect if the vulnerability is accepted or
declined, etc.
