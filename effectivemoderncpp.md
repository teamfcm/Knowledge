# Effective Modern C++
*Scott Meyers* (2014)

## Deducing types

+ [Item1](effectivemodern/item1.md) : Understand template type deduction
+ Item2 : Understand auto type deduction
+ Item3 : Understand decltype
+ Item4 : Know how to view deduced types

## Auto

+ Item5 : Prefer auto to explicit type declarations 
+ Item6 : Use the explicitly typed initializer idiom when auto deduces undesired types

## Moving to Modern C++

+ Item7 : Distinguish between () and {} when creating objects
+ Item8 : Prefer nullptr to 0 and NULL
+ Item9 : Prefer alias declarations to typedefs
+ Item10 : Prefer scoped enums to unscoped enumes
+ Item11 : Prefer deleted functions to private undefined ones
+ Item12 : Declare overriding functions override
+ Item13 : Prefer const_iterators to iterators
+ Item14 : Declare functions noexcept if they won't emit exceptions
+ Item15 : Use constexpr whenever possible
+ Item16 : Make const member functions thread safe
+ Item17 : Understand special member function generation

## Smart pointers

+ Item18 : Use std::unique_ptr for exclusive ownership resource management
+ Item19 : Use std::shared_ptr for shared ownership resource management
+ Item20 : Use std::weak_ptr for std::shared_ptr like pointers that can dangle
+ Item21 : Prefer std::make_unique and std::make_shared to direct use of new
+ Item22 : When using the Pimpl idiom, define special member functions in the implementation file

## Rvalue References, Move Semantics, and Perfect Forwarding

+ Item23 : Understand std::move and std::forward 
+ Item24 : Distinguish universal references from rvalue references
+ Item25 : Use std::move on rvalue references, std::forward on universal references
+ Item26 : Avoid overloading on universal references
+ Item27 : Familiarize yourself with alternatives to overloading on universal references
+ Item28 : Understand reference collapsing
+ Item29 : Assume that move operations are not present, not cheap and not used
+ Item30 : Familiarize yourself with perfect forwarding failure cases

## Lambda expressions

+ Item31 : Avoid default capture modes
+ Item32 : Use init capture to move objects into closures
+ Item33 : Use decltype on auto&& parameters to std::forward them
+ Item34 : Prefer lambdas to std::bind

## The Concurrency API

+ Item35 : Prefer task-based programming to thread-based
+ Item36 : Specify std::launch::async if asynchronicity is essential
+ Item37 : Make std::threads unjoinabled on all paths
+ Item38 : Be aware of varying thread handle destructor behavior
+ Item39 : Consider void futures for one-shot event communication
+ Item40 : Use std::atomic for concurrency volatile for special memory

## Tweaks 

+ Item41 : Consider pass by value for copyable parameters that are cheap to move and always copied
+ Item42 : Consider emplacement instead of insertion