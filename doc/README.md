# `1i` 📚 Documentation
> Concepts & usage

## Overview

The interface is the middle point where two ends meet. The interval between sticks. The magical place where something becomes something else: where electricity becomes sound, and vice versa; where words become compute, and compute becomes pixels; where machine and Man meet.

In programming, an interface is where an object may be connected with. As input, the interface is what the object needs, and more generally understands; as output, it's what the object will or may do and say. You use it everyday when you call something with known arguments—a simple URL issued in an address bar, a password, and yes a function or class. You know the power of interfaces that let you change the implementation on any side without impacting the other, as long as you preserve the interface. Zooming out at the module level, the interface becomes the way to interact with those objects, from simple `import` statements to more involved packaging, distribution, and deployment.

This is where `1i` comes in. It brings **the power of the 1-liner to perform all this boilerplate work needed for packaging, distribution, and deployment**. All of which generally sits way outside the compentency realm and core skill set of the programmer.

Why should you have to care how `pip` or `cargo` want things besides application design? You can, and you should if that's your thing, but generally the beauty of programming lies in the interface between some `def func(…)` in the code and a terminal `$ func …` command that does the thing. Everything in-between these two steps is hinderance at best, obstacles at worst. 1i intends to solve that problem in the most general manner possible—ideally, for all languages, to all platforms, with all package managers. This is obviously a community effort by principle, wherein one circumstantial ambassador of each combination comes to fix what's broken since the last one came. It's the textbook example of doing it one time and one time only for the entire population of programmers worldwide. And it's hopefully a meaningful way to help grow said population, by onboarding many more who otherwise couldn't, or wouldn't contribute.

## How it works

Everything is a list. Or graph. Some namespace. `1i` leverages a simple domain to namespace all the things into their proper category.

`https://` **`NAMESPACE`** . `1i.is` / **`TARGET`**

For instance, `https://weather.1i.is/linux/pip` to install `fasthtml` on Linux using `pip`.  
The resulting command usually looks something like `TARGET install NAMESPACE`, e.g. `pip install weather`, `apt install weather`.

You only have to care about your code in some `NAMESPACE` (in practice: proper folders under a root project name).  
`1i` will make all the possible `TARGET`s for you in one command.

The above `NAMESPACE` example is a bit too simplistic: in practice, we would prefer a two-part subdomain in the form `package.vendor.1i.is`, like `fasthtml.answerai.1i.is`. When the vendor and the package name are the same, then we may imply it with a single subdomain `name.1i.is` (that's what happens when you simply reach `1i.is`: it's a contraction of `1i.1i.1i.is`). We suggest you reproduce this scheme if deploying the `1i` paradigm to your own domain.




