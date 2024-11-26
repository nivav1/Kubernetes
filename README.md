# Kubernetes Project_1

# This simple project takes a frontend, backend and database setup to enable registering users from the web into the database

# To apply this project, you need to have docker engine, minikube and kubectl installed.

# Start minikube, apply the files in prequeries/ then deployment/, services/ and ingress/ using kubectl apply -f [file_name]

# Run "minikube addons enable ingress" to enable Nginx

# To see the application, type "minikube ip" in the terminal and copy the ip into your internet search bar

# For DNS(only locally), edit /etc/hosts above the "# end of section" by adding "[cluster's_ip_address] super.simple.register.com" and enter super.simple.register.com in the search bar
