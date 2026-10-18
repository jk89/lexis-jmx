# lexis-jmx

<table><tr>
<td valign="middle" width="160"><img src="https://raw.githubusercontent.com/jk89/lexisdb/develop/lexis-icon.svg" width="160" height="196" alt="Lexis"></td>
<td valign="middle">

The JMX proxy for [Lexis](https://github.com/jk89/lexisdb), a fork of ScyllaDB
that replaces the Murmur3 partitioner with byte-ordered partitioning, built on
tablets. It exposes a Lexis node's REST API over JMX, for `nodetool` from
[lexis-tools-java](https://github.com/jk89/lexis-tools-java).

</td>
</tr></table>

It works with Lexis unchanged.

Docker image: `docker pull 0x6a6f6e6e79/lexis-jmx`

## Base and licence

Forked from ScyllaDB's scylla-jmx at tag `scylla-6.2.0`. Licensed under the
GNU AGPL ([LICENSE.AGPL](LICENSE.AGPL), [NOTICE](NOTICE)).

The upstream README is kept unchanged in [README_SCYLLA.md](README_SCYLLA.md).