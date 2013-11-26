---
layout: post
title: "Block Objects in iOS"
date: 2013-11-25 09:22:24 -0600
comments: true
categories: 
---

“Block objects can either be inline or coded as independent blocks of code.
Let’s start with the latter type. Suppose you have a method in Objective-C that
accepts two integer values of type NSInteger and returns the difference of the
two values, by subtracting one from the other, as an NSInteger:”


    - (NSInteger) subtract:(NSInteger)paramValue from:(NSInteger)paramFrom { 
    return paramFrom - paramValue;
    }


pure C function that provides the same functionality to get one step closer to
learning the syntax of block objects:

    NSInteger subtract(NSInteger paramValue, NSInteger paramFrom){
        return paramFrom - paramValue;
}

You can see that the C function is quite different in syntax from its
Objective-C counterpart. Now let’s have a look at how we could code the same
function as a block object:

    NSInteger (^subtract)(NSInteger, NSInteger) = ^(NSInteger paramValue,
        NSInteger paramFrom) {        
                return paramFrom - paramValue;
                    

};

Suppose we have a function in C that takes a parameter of type NSUInteger (an
unsigned integer) and returns it as a string of type NSString. Here is how we implement this in C:
    NSString* intToString (NSUInteger paramInteger){
    
        return [NSString stringWithFormat:@"%lu",
                    (unsigned long)paramInteger];
                        

}

The block object equivalent of this C function is:
    NSString* (^intToString)(NSUInteger) = ^(NSUInteger paramInteger){
    
        NSString *result = [NSString stringWithFormat:@"%lu",
                                (unsigned long)paramInteger];
                                    
                                        return result;
                                            

};

