# NBA Games Alert System

This project is an NBA Games Alert System designed to provide real-time game updates via SMS and email. It leverages AWS services and the NBA API to deliver live scores, schedules, and game statuses, using event-driven architecture.

## Features

- **Live Game Updates**: Retrieves scores, schedules, and game statuses from the NBA API.
- **Real-Time Notifications**: Sends alerts via SMS and email using Amazon SNS.
- **Scheduled Automation**: Uses Amazon EventBridge to trigger notifications on game days.
- **Serverless Architecture**: Powered by AWS Lambda for processing and integration.
- **Secure Design**: Enforces least-privilege access through IAM roles and policies.

## Technologies Used

- **Cloud Provider**: AWS
- **AWS Services**: Lambda, SNS, EventBridge
- **Programming Language**: Python
- **External API**: NBA API
- **IAM Policies**: Implemented for secure and restricted access
  
## Key Takeaways

- **Event-Driven Architecture**: Automating notifications with EventBridge and Lambda.
- **Serverless Workflows**: Efficient and scalable design using AWS services.
- **Security Best Practices**: Applying IAM roles for least-privilege access.
- **API Integration**: Handling external API calls within cloud-based workflows.

## Challenges and Solutions

- **Lambda Timeout Errors**:
  - **Cause**: High latency while fetching data from the NBA API.
  - **Solution**: Increased Lambda timeout to 10 seconds for smoother API integration.

## Future Enhancements

- Add support for multiple sports and APIs.
- Include a web-based dashboard for game tracking.
- Integrate advanced filtering for user-specific game alerts.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Feel free to contribute by opening issues or submitting pull requests to improve the system!
