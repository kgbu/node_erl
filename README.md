node_erl
======

Just a concept making of Node.Erlang. Based on Erlang terms for JSON. Weaving browser message passing nano-services.

Browser side
----

Use Erlang terms for JSON.
But, in most case, Erlang term/record is very similer to JSON

+ JSON/Erlang terms schema transformation

This is already implemented in various web application products 

+ nano-service base browser

Rendering engine can be used without modification while DOM <-> process tree matching is assured.

Each DOM element is managed as Erlang process!

+ V8 base BEAM VM

performance may be just lower. But, this is very portable way to implement BEAM.

Already forerunning project exists. 
http://www.erlang-factory.com/conference/SFBay2011/speakers/YuriiRashkovskii

Erlang interface for V8 : https://github.com/beamjs/erlv8
This is not exactly match of 'BEAM on V8' but its interface architecture is MUST TO READ for me, anyway.

Server side
----

Just a plain Erlang node.
But communicate with TLS protected communication path.

Protocol
----

HTTP1,2 or pub/sub style, or just Erlang node conneciton over TLS

for Server side distribution, Docker link like feature maybe useful (not confirmed)
