# pubsub2listener

Listen to pubsub events and call a listener

composer require Entanet/pubsub2listener

Include Entanet\PubSub2Listener\PubSub2ListenerProvider::class in providers

Add to listen array in EventServiceProvider
'topic' => [
    'listener1',
    'listener2'
]