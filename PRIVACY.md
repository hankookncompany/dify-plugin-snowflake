# Privacy Policy

This plugin connects to Snowflake to generate and execute SQL queries provided by the user.

## 1. Data Collection

This plugin **does not collect, store, or process** any personal data from users. Specifically:

- ❌ No names, email addresses, phone numbers, or government identifiers are collected.
- ❌ No IP addresses, device identifiers, or location data are collected.
- ❌ No user behavioral or financial data are stored or analyzed.

The plugin acts as a thin SQL execution layer and relies solely on credentials and queries passed at runtime by the Dify platform.

## 2. Use of Third-Party Services

This plugin uses:

- [Snowflake](https://www.snowflake.com/privacy-policy/) — as the backend data engine.

Snowflake credentials are passed securely at runtime via the Dify platform and are not logged or persisted by the plugin itself.

Please refer to [Snowflake's Privacy Policy](https://www.snowflake.com/privacy-policy/) for their handling of data.

## 3. Data Storage

This plugin does **not persist any data**. All SQL query results are returned immediately via Dify’s plugin runtime interface and are not cached or logged by the plugin.

## 4. Authentication

The plugin uses credentials passed from Dify securely to authenticate to Snowflake. These are used **transiently** and are **not stored**.

## 5. Summary

This plugin operates without collecting or storing any personal data. All user data remains within Dify and Snowflake environments. No additional processing or third-party sharing is performed.

If you have any questions about this plugin's data handling, please contact the developer.