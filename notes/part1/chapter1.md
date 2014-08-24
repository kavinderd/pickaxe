#Getting Started

###What did I learn?
  This first chapter is largely centered around setting up Ruby on one's system.  A lot of what I read was familiar as I have done it on numerous occasions, but it wasn't perhaps information that I could relay with any skill.

  The topics covered were using RVM to install Ruby, using IRB, and writing some basic code in a ruby file and running it. 

- RVM: Ruby version manager, other ruby solutions weren't mentioned perhaps this was due to RVM's longer existence in the community
- IRB: *interactive ruby* a repl that allows a user to kick the tires with ruby
- running ruby code: ruby ___.rb runs any ruby code that's in the file.  Alternatively, a file can have no extension and have a shebang on the first line,
  `#! /usr/bin/ruby` which will allow the file to be marked as executable and will pick up the user's active ruby when running.

### What problems were addressed?

  There was no discussion of why Ruby?  But RVM is clearly a solution addressing the problem of managing many different MRI versions and other rubies as well.  Since Ruby isn't compiled, having an interactive shell is perhaps less a solution to a Ruby problem, but a compiled-language problem that Ruby can give the solution to without ever having to deal with the problem. 

### What other solutions exist?

  The only varying alternative for any of the material covered in this first chapter is RVM. RVM has come under criticism for trying to do too much.  Other solutions that exist are rbenv, and chruby.  Personally, I have not used the other two and haven't really felt the pain of RVM.

###How have I applied this knowledge?

- I use rvm daily
- I use irb/pry daily
- I write .rb and command line executable ruby files regularly

###How can I extend this knowledge?

- I can attempt to use other ruby version managers
- I can become more familiar with all the options irb provides

### What don't I understand?

- I'm not too clear about the differences and tradeoffs between RVM, rbenv and chruby
- I enjoy ruby, but am not entirely capable of answering Why Ruby over X?
- What's lost with dynamic languages
- Why doesn't ruby work well on Windows

###Can I explain what I learned? Have I?

 I feel I can explain enough about Ruby, RVM. and IRB to get someone as far as this chapter has provided. 

###Have I mastered what I learned?

 No.
