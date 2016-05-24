# statsd-console-json-backend

StatsD backend for logging metrics to stdout in JSON format.

## Usage

1. Install package into your project:
  ```
  $ npm install statsd-console-json-backend
  ```

2. Configure your StatsD backend. Example StatsD configuration:
  ```js
  {
    backends: [ 'statsd-console-json-backend' ]
  }
  ```

  More information on configuring backends at: https://github.com/etsy/statsd/blob/master/docs/backend.md
