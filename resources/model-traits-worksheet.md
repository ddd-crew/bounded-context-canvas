# Model Traits worksheet

A model is likely to be described by a number of different traits. Review the list below and choose which one applies to the context you are working on or think of your own traits.

| Trait | Heuristic |
|---|---|
| Specification Model | Produces a document describing a job/request that needs to be performed. Example: Advertising Campaign Builder |
| Execution Model | Performs or tracks a job. Example: Advertising Campaign Engine |
| Audit Model | Monitors the execution. Example: Advertising Campaign Analyser |
| Approver | Receives requests and determines if they should progress to the next step of the process. Example: Fraud Check |
| Enforcer | Ensures that other contexts carry out certain operations. Example: GDPR Context (ensures other contexts delete all of a user’s data) |
| Octopus Enforcer | Ensures that multiple/all contexts in the system all comply with a standard rule. Example: GDPR Context (as above) |
| Interchanger | Translates between multiple ubiquitous languages. |
| Gateway | Sits at the edge of a system and manages inbound and/or outbound communication. Example: IoT Message Gateway |
| Gateway Interchange | The combination of a gateway and an interchange. |
| Dogfood Context | Simulates the customer experience of using the core bounded contexts. Example: Whitelabel music store |
| Bubble Context | Sits in-front of legacy contexts providing a new, cleaner model while legacy contexts are being replaced.  |
| Autonomous Bubble | Bubble context which has its own data store and synchronises data asynchronously with the legacy contexts. |
| Brain Context (likely anti-pattern) | Contains a large number of important rules and many other contexts depend on it. Example: rules engine containing all the domain rules |
| Funnel Context | Receives documents from multiple upstream contexts and passes them to a single downstream context in a standard format (after applying its own rules). |
| Engagement Context | Provides key features which attract users to keep using the product. Example: Free Financial Advice Context |