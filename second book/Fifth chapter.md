1-. Advantage and disadvantage of synchronous Recopilacion
  R= The advantage of synchronous replication is that the follower is guaranteed to have an up-to-date copy of the data that is consistent with the leader. If the leader 
  suddenly fails, we can be sure that the data is still available on the follower. The disadvantage is that if the synchronous follower doesn’t respond (because it has crashed, 
  or there is a network fault, or for any other reason), the write cannot be processed.
