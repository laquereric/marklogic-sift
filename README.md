# marklogic-sift
A library that allows use of sift (MongoDB) queries against MarkLogic databases.

The Sift project (see https://github.com/crcn/sift.js/ - Use Mongodb queries to filter data in JavaScript) provides tools needed to filter arbitrary lists of Javascript objects. AS one facet of MarkLogic's capabilities, it can operate as a JSON object store. It sould be noted: 
  
  Filtering objects is considered an anti-pattern by MarkLogic
  Sift overlaps filter functions provided by MarkLogic APIs
  MarkLogic provides indexing and triple facilties that can be orders of magnitude more efficient than ANY filter function
    sift - Implemented with MarkLogic SJS running in multiple V8 instances
    cts - Internally Implemented with MarkLogic library calls implmented in XQUERY and C++
    execution - In either case - The MarkLogic cluster provides distributed execution, document caches and other perfomance features.
    
 See https://www.marklogic.com/ for more infrormation regarding MarkLogic.
