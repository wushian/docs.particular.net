To get full control over the conversation ID, a custom convention can be registered:

snippet: custom-conversation-id-convention

This is useful to avoid setting the conversation ID when sending individual messages but rather apply a convention using a custom attribute, inheriting from an interface, using reflection based on message types, or some other method.
