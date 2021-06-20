# Seq

## All 100 methods in the Seq library in F# 5

1. [Seq.allPairs](#seq.allpairs)
1. Seq.append
1. Seq.average
1. Seq.averageBy
1. Seq.cache
1. Seq.cast
1. Seq.choose
1. Seq.chunkBySize
1. Seq.collect
1. Seq.compareWith
1. Seq.concat
1. Seq.contains
1. Seq.countBy
1. Seq.delay
1. Seq.distinct
1. Seq.distinctBy
1. Seq.empty
1. Seq.exactlyOne
1. Seq.except
1. Seq.exists
1. Seq.exists2
1. Seq.filter
1. Seq.find
1. Seq.findBack
1. Seq.findIndex
1. Seq.findIndexBack
1. Seq.fold
1. Seq.fold2
1. Seq.foldBack
1. Seq.foldBack2
1. Seq.forall
1. Seq.forall2
1. Seq.groupBy
1. Seq.head
1. Seq.indexed
1. Seq.init
1. Seq.initInfinite
1. Seq.isEmpty
1. Seq.item
1. Seq.iter
1. Seq.iter2
1. Seq.iteri
1. Seq.iteri2
1. Seq.last
1. Seq.length
1. Seq.map
1. Seq.map2
1. Seq.map3
1. Seq.mapFold
1. Seq.mapFoldBack
1. Seq.mapi
1. Seq.mapi2
1. Seq.max
1. Seq.maxBy
1. Seq.min
1. Seq.minBy
1. Seq.ofArray
1. Seq.ofList
1. Seq.pairwise
1. Seq.permute
1. Seq.pick
1. Seq.readonly
1. Seq.reduce
1. Seq.reduceBack
1. Seq.replicate
1. Seq.rev
1. Seq.scan
1. Seq.scanBack
1. Seq.singleton
1. Seq.skip
1. Seq.skipWhile
1. Seq.sort
1. Seq.sortBy
1. Seq.sortByDescending
1. Seq.sortDescending
1. Seq.sortWith
1. Seq.splitInto
1. Seq.sum
1. Seq.sumBy
1. Seq.tail
1. Seq.take
1. Seq.takeWhile
1. Seq.toArray
1. Seq.toList
1. Seq.transpose
1. Seq.truncate
1. Seq.tryExactlyOne
1. Seq.tryFind
1. Seq.tryFindBack
1. Seq.tryFindIndex
1. Seq.tryFindIndexBack
1. Seq.tryHead
1. Seq.tryItem
1. Seq.tryLast
1. Seq.tryPick
1. Seq.unfold
1. Seq.where
1. Seq.windowed
1. Seq.zip
1. Seq.zip3

Seq.empty
// { }


### Seq.allPairs
// Cartesian Product
Seq.allPairs (seq { 1; 2 }) (seq { 'a'; 'b' })
// seq { (1, 'a'); (1, 'b'); (2, 'a'); (2, 'b') }
