
event driven api
#### web hooks

	 client register to event webhook : events + callback url
	
	 pitfall
	 backend responsible for failure
	 firewall : url publicly accessible
	 Noise : many events in a short time(multiple events) whats app : multiple msg notification

#### web sockets : continuos communication : Bidirectional : low latency : low http headers

      client <---> server
	    client is responsible for communication
	    scalabality challenges
	
#### HTTP streaming 

	normal http  : finite response
	using HTTP streaming : server response is indefinite : server keep on sending
	
    1. non server : two backend server communicating

  	chunked : non browser clients  : data comes in chunks

	  2. server sent events : twitter : browser
  	
  	cons
  	bidirectional challenging
  	buffer 
