# WIZnet W5100 IC #

WIZnet is a South Korean company that creates semiconductors for connectivity.  More specifically, WIZnet has created a line of integrated circuits that have a hardware based TCP/IP stack and associated embedded Ethernet interface such as MAC and PHY.  The Spinneret Web Server project utilizes the W5100 IC from WIZnet.

The W5100 IC product details can be found at the WIZnet [W5100 product page](http://www.wiznet.co.kr/Sub_Modules/en/product/Product_Detail.asp?cate1=5&cate2=7&cate3=26&pid=1011):

The basics of the W5100 IC include:
  * Two types of MCU to W5100 interface - SPI and parallel (indirect address or direct addressing)
  * Support Hardwired TCP/IP Protocols TCP, UDP, ICMP, IPv4 ARP, IGMP, PPPoE, Ethernet
  * 10BaseT/100BaseTX Ethernet PHY embedded
  * Support Auto Negotiation (Full-duplex and half duplex)
  * Support Auto MDI/MDIX
  * Support ADSL connection (with support PPPoE Protocol with PAP/CHAP Authentication mode)
  * Supports 4 independent sockets simultaneously
  * Internal 16Kbytes Memory for Tx/Rx Buffers
  * 3.3V operation with 5V I/O signal tolerance

If you are wanting to experiment with the W5100 IC, but don't want to design your board, then of course you can use the Spinneret which marries the Propeller and the W5100 together.  More over, if you are wanting a module, something that is plug and play so you can experiment with other microcontroller or something to integrate into your design, you should consider the WIZnet [WIZ812MJ module](http://www.wiznet.co.kr/Sub_Modules/en/product/Product_Detail.asp?cate1=5&cate2=42&cate3=0&pid=1026).

# References and Resources #

There are several references and resource you could use to gain knowledge and insight to working with the W5100. The following is a list of places to start off the treasure hunt.

  * [W5100 product page](http://www.wiznet.co.kr/Sub_Modules/en/product/Product_Detail.asp?cate1=5&cate2=7&cate3=26&pid=1011)
  * [Circuit Cellar 2007 iEthernet Contest](http://www.circuitcellar.com/Wiznet/)
  * [Circuit Cellar iEthernet Bootcamp Article](http://www.circuitcellar.com/archives/viewable/Eady208/2.html)
  * [Sparkfun W5100 Product Site](http://www.sparkfun.com/products/9471)