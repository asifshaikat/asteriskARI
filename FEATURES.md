| #  | Asterisk REST Interface (ARI)                     | Asterisk Gateway Interface (AGI)                  | Asterisk Manager Interface (AMI)                       |
|----|-------------------------------------------------|--------------------------------------------------|------------------------------------------------------|
| 1  | Originate channels                             | Interactive Voice Response (IVR) implementation  | Real-time call monitoring                           |
| 2  | Answer channels                               | Database integration                             | Originate calls                                    |
| 3  | Hang up channels                              | External script execution                        | Answer calls                                       |
| 4  | Mute/unmute channels                          | Text-to-Speech (TTS) conversion                 | Hang up calls                                      |
| 5  | Pause/unpause channels                        | Speech recognition                              | Transfer calls                                     |
| 6  | Control bridges (conference rooms)           | DTMF tone detection and handling                | Mute/unmute channels                               |
| 7  | Play audio to channels                       | Call control (answer, hang up, transfer)       | Pause/unpause channels                             |
| 8  | Record channels                              | Event notification handling                     | Park calls                                         |
| 9  | Subscribe to events (WebSockets/HTTP)       | Channel manipulation                            | Control call queues                                |
| 10 | Transfer calls                               | Dynamic call routing                            | Access channel details (e.g., caller ID, call duration) |
| 11 | Manage applications                         | Call recording control                         | Playback audio files to channels                  |
| 12 | Manipulate channel variables                | Access to channel variables                    | Record calls                                       |
| 13 | Execute dialplan applications               | Custom call processing logic                   | Set channel variables                              |
| 14 | Control device state                        | Integration with external APIs                 | Execute CLI commands                               |
| 15 | Manage media playback and recording        | Real-time call monitoring                      | Manage conference bridges                         |
| 16 | Receive DTMF input                          | IVR menu navigation                           | Manage SIP peers                                  |
| 17 | Authenticate users                          | Error handling and logging                    | Receive event notifications for channel state changes |
| 18 | Control endpoint registration              | Call queue management                         | Generate call detail records (CDRs)               |
| 19 | Manage channel playback                    | Interactive call scripting                    | Manage voicemail boxes                            |
| 20 | Execute AGI scripts                        | Multi-language support                        | Control call forwarding                          |
| 21 | Bridge channels                            | Secure authentication and authorization       | Manage call parking lots                         |
| 22 | Control channel playback speed            | Integration with CRM systems                  | Monitor system resources (CPU, memory, etc.)     |
| 23 | Monitor channel events                     | Integration with billing systems              | Control channel redirection                      |
| 24 | Query channel details                      | Voicemail management                         | Execute AGI scripts                              |
| 25 | Handle channel stasis events               | Call screening and filtering                  | Query and manipulate call queues                 |
| 26 | Access to Asterisk configuration          | Call conferencing control                     | Interact with external databases                 |
| 27 | Perform call parking                       | Perform call transfers with attended or blind transfer options |  |
| 28 | Manage channel recordings                  | Access to voicemail information and settings |  |
| 29 | Control channel speech recognition        | Call prioritization                          | Control music on hold                            |
| 30 | Manage channel SIP subscriptions          | Real-time call analytics                     | Manage SIP registrations                        |
| 31 | Interact with external databases          | Call logging and reporting                   | Access to Asterisk configuration information     |
| 32 | Handle channel media events               | Call statistics aggregation                  | Set caller ID on outbound calls                 |
| 33 | Manipulate channel dialplan               | Quality monitoring                           | Bridge multiple channels together               |
| 34 | Control channel media resources           | Integration with messaging platforms         | Perform call monitoring and whisper/barge functionalities |
| 35 | Implement custom event handling logic     | Integration with email systems               | Control call routing based on conditions        |
| 36 | Perform call forwarding                   | Integration with calendar systems            | Authenticate and authorize users                |
| 37 | Manage endpoint state                     | Integration with directory services          | Manage call waiting                             |
| 38 | Access to channel media properties        | Integration with payment gateways            | Retrieve and manipulate voicemail messages      |
| 39 | Implement custom channel handling logic   | Integration with location services           | Generate call reports                           |
| 40 | Control channel ringback                  | Integration with emergency services          | Perform call screening                          |
| 41 | Implement custom bridge handling logic    | Integration with customer support systems    | Handle call timeouts                            |
| 42 | Retrieve bridge details                   | Integration with social media platforms      | Control call recording settings                 |
| 43 | Implement custom application logic        | Integration with IoT devices                 | Manage call queues in real-time                 |
| 44 | Handle endpoint device state changes      | Integration with chatbots                    | Interact with external APIs                     |
| 45 | Manage channel DTMF events                | Integration with video conferencing systems  | Control call forwarding based on time of day or caller ID |
| 46 | Control channel ringing                   | Integration with speech synthesis engines    | Access to detailed call information (trunk usage, call duration, etc.) |
| 47 | Manage channel speech synthesis           | Integration with speech recognition engines  | Integration with CRM systems                    |
| 48 | Interact with channel variables           | Integration with natural language processing systems | Implement custom call routing logic             |
| 49 | Control channel text messages             | Integration with machine learning models     | Monitor and manage SIP trunk registrations      |
| 50 | Handle channel hangup events              | Integration with blockchain technologies     | Implement call restrictions and permissions     |
