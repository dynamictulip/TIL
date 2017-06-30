# Glossary
This is a list of technical things and a brief overview of what they are and where to get more info!

## Message Queues
#### 0MQ
<http://zeromq.org/>

#### Apache ActiveMQ
<http://activemq.apache.org/>

#### NServiceBus
<https://particular.net/nservicebus>

#### RabbitMQ
<https://www.rabbitmq.com/>

## Serialisation
#### Bond (Microsoft)
Bond is an open source, cross-platform framework for working with schematized data. It supports cross-language serialization/deserialization and powerful generic mechanisms for efficiently manipulating data. Bond is broadly used at Microsoft in high scale services.

<https://github.com/Microsoft/bond>

#### Cap'n Proto
Cap’n Proto is an insanely fast data interchange format and capability-based RPC system. Think JSON, except binary. Or think Protocol Buffers, except faster. In fact, in benchmarks, Cap’n Proto is INFINITY TIMES faster than Protocol Buffers.

This benchmark is, of course, unfair. It is only measuring the time to encode and decode a message in memory. Cap’n Proto gets a perfect score because there is no encoding/decoding step. The Cap’n Proto encoding is appropriate both as a data interchange format and an in-memory representation, so once your structure is built, you can simply write the bytes straight out to disk!

<https://capnproto.org/encoding.html>

#### JSON
JSON (**J**ava**S**cript **O**bject **N**otation) is a lightweight data-interchange format. It is easy for humans to read and write. It is easy for machines to parse and generate. It is based on a subset of the JavaScript Programming Language, Standard ECMA-262 3rd Edition - December 1999. JSON is a text format that is completely language independent but uses conventions that are familiar to programmers of the C-family of languages, including C, C++, C#, Java, JavaScript, Perl, Python, and many others. These properties make JSON an ideal data-interchange language.

#### ProtoBuf / Protocol Buffers (Google)
Protocol buffers are a flexible, efficient, automated mechanism for serializing structured data – think XML, but smaller, faster, and simpler. You define how you want your data to be structured once, then you can use special generated source code to easily write and read your structured data to and from a variety of data streams and using a variety of languages. You can even update your data structure without breaking deployed programs that are compiled against the "old" format.

<https://developers.google.com/protocol-buffers/docs/overview>
<http://blog.codeclimate.com/blog/2014/06/05/choose-protocol-buffers/>
