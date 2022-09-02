# tmf-ids-dataapps - Ran Slicing Usecase

## Build the apps
'''
cd csp-resource-management
sudo docker image rm ashokkumarta/csp-resource-management:latest
sudo docker build -t ashokkumarta/csp-resource-management:latest .
sudo docker push ashokkumarta/csp-resource-management:latest
cd ../csp-load-optimizer
sudo docker image rm ashokkumarta/csp-load-optimizer:latest
sudo docker build -t ashokkumarta/csp-load-optimizer:latest .
sudo docker push ashokkumarta/csp-load-optimizer:latest
cd ../csp-ran-slice-allocation
sudo docker image rm ashokkumarta/csp-ran-slice-allocation:latest
sudo docker build -t ashokkumarta/csp-ran-slice-allocation:latest .
sudo docker push ashokkumarta/csp-ran-slice-allocation:latest
cd ../subscriber-1-demand-forecast
sudo docker image rm ashokkumarta/subscriber-1-demand-forecast:latest
sudo docker build -t ashokkumarta/subscriber-1-demand-forecast:latest .
sudo docker push ashokkumarta/subscriber-1-demand-forecast:latest
cd ../subscriber-1-optimizer-feedback
sudo docker image rm ashokkumarta/subscriber-1-optimizer-feedback:latest
sudo docker build -t ashokkumarta/subscriber-1-optimizer-feedback:latest .
sudo docker push ashokkumarta/subscriber-1-optimizer-feedback:latest
cd ../subscriber-1-allocation-confirmation
sudo docker image rm ashokkumarta/subscriber-1-allocation-confirmation:latest
sudo docker build -t ashokkumarta/subscriber-1-allocation-confirmation:latest .
sudo docker push ashokkumarta/subscriber-1-allocation-confirmation:latest
cd ..
'''


