Welcome to your new dbt project!

### Using the starter project

Try running the following commands:
- dbt run
- dbt test

### Structure
dbt/   
  ├── analysis/   
  ├── data/   
  ├── macros/   
  ├── models/                    	# Should   contain your model structure and the project definition ".yml" file  
    └── schema.yml       
    └── customers.sql      
    └── stg_customers.sql     
    └── stg_orders.sql    
  ├── profile/                 	#contain the necessary "profiles.yml" file to run your project              
    └── profiles.yml       
    └── bigquery-keyfile.json        
  ├── snapshots/    
  ├── tests/        
  ├── target/			              # contain the "manifest.json" file obtained with "dbt docs generate"    
    └── manifest.json        
  ├── README.md      
  └── dbt_project.yml


### Resources:
- Learn more about dbt [in the docs](https://docs.getdbt.com/docs/introduction)
- Check out [Discourse](https://discourse.getdbt.com/) for commonly asked questions and answers
- Join the [chat](https://community.getdbt.com/) on Slack for live discussions and support
- Find [dbt events](https://events.getdbt.com) near you
- Check out [the blog](https://blog.getdbt.com/) for the latest news on dbt's development and best practices

