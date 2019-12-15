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

`<% provide(:[variable_name],"[Word]") %>`  
it mean  
`$[variable_name] = Word`  
  
To use the variable, Just
  `<%= yield(:title) %>`  
wherever you want to use.



