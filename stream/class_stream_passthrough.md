
The `stream.PassThrough` class is a trivial implementation of a [Transform][]
stream that simply passes the input bytes across to the output. Its purpose is
primarily for examples and testing, but there are some use cases where
`stream.PassThrough` is useful as a building block for novel sorts of streams.
