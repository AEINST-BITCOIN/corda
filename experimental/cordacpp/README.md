# Corda C++ decoding support

This code demonstrates how to read Corda serialized AMQP messages without any Java, 
just using C++14. It exists primarily to show the cut-lines for reimplementors, and
to help people explore the wire format at a low level.

You will need to install Apache Qpid Proton C++ and cmake to be able to compile this.

```bash
./gradlew experimental:cordacpp:cordacpp
```

# TODO

- [ ] Still working on parsing a full cash movement transaction
- [ ] Enums
- [ ] Evolution
- [ ] Back-references
- [ ] Serialization not just deserialization
- [ ] Demonstrate how to calculate the Merkle tree
- [ ] Demonstrate how to check the signatures
- [ ] Generics in FungibleAsset aren't quite right yet.