# Method
  
* ###  describe 
  All behavior describe as a calling method.   
  One describes has many examples.  
  Describe the method's arguments specified string or const integer which explain the behavior.
  There are 2 ways to explain describe.  
                     
  `describe Array, "When empty" do...`  
  or  
  `describe "An empty array" do...`
-----

* ###  example
   Example method is equivalent to the block of describe method.  
   Use this method to write an expectation.  
   This is RSpec version of  `assert_XXX`   
   How to write is 
     
   `it "should..." do ... end`   
-----

* ### it
    it method has two kind of arguments.
    One is string which describe the expectation.  
    Other is the block which write expectation.  
    Exp is   
    `descrive Array, "when empty" do`   
       `  ...`   
       `  it "should be empty do`   
         `  @empty_array.should be_empty  `  
       `  end`  
       `  ...`  
     `  end ` 
-----
* ### before/after
    This method is used as a hook to descript preprocessing and Post-processing.
    before/after method have arguments (:each or :all).  
    :all arg is run only one time and :each arg is run every time when each example are called.  
    Default is :each method.  
    After method is call in assending order.
    
    `before/after(:each/all) do `    
    `  pre/post-processing`  
    `end  `  
----

* ###

     
    this method are used as hook to descript the preprocessing and Post-processing.
