# Create or delete

* `rails g controller [controller_name] [action_name]`  
create a controller and action
  
  
* `rails destroy controller [controller_name] [action_name]`  
destroy a controller and it's action  
   
* `rails g model [model_name] [column_name]:[column_type]`  
create a model with column  
  
* `rails destroy model [model_name]`  
destroy a model  
  
* `rails db:migrate`  
change the databese's migration

* `rails db:rollback`  
Return to the previout state  
  
* `rails db:migrate VERSION=0`  
Return to the initial state

# With testing  

* `assert_response :success`  
check the resopnse from request

* `assert_select [tag_name],[optional string]`
Check if there is a specific string in the tag  
  
# In view  

* `<% provide(:[variable_name],"[Word]") %>`  
it mean  
`$[variable_name] = Word`  
  
* `<%= yield(:title) %>`  
use the variable,wherever you want to use.  


* `<%= render 'layouts/(file_name)' %>`   
make partial. render html has to be written in app/views/layouts/_(file_name)  

# with instance

* `[instance_A] = [instance_B].dup`
copy [instance_B]to [instance_A]



