# Test Website for Customer Display Application

Customer Display is intended to be used as a display application which shows the content like Products, takes input from Customers etc., is controlled by a POS website.

The test website created to act as POS website that controls the Customer Display application is https://erply-test-display.web.app/#/.

## How to control Customer Display using Test POS Website?

1. Open Test POS Website (https://erply-test-display.web.app/#). You'll be show the following screen.

   |                Choose App                |
   | :--------------------------------------: |
   | <img src="images/POS Choose App.png"  /> |

   Now, choose Customer Display to test the application.

2. Once you choose the application, you will be shown the following screen.

   |              Enter POS Code              |
   | :--------------------------------------: |
   | <img src="images/POS Enter Code.png"  /> |

   Now, enter the code and click 'Join Channel POS'

3. You will be now be shown a code that your are supposed to enter on Customer Display Application.

   |              POS Code              |
   | :--------------------------------: |
   | <img src="images/POS Code.png"  /> |

   You can enter the code on Display and click on 'Submit'

   |          Enter POS Code on Display           |
   | :------------------------------------------: |
   | <img src="images/Display Enter Code.png"  /> |

4. At this point, the Customer Display app will be waiting for config from Test POS Website.

   |              Display Waiting              |
   | :---------------------------------------: |
   | <img src="images/Display Waiting.png"  /> |

   Now on the Test POS Website you will be shown the configuration JSON that needs to be sent.

   |                Send Configuration                |
   | :----------------------------------------------: |
   | <img src="images/POS Send Configuration.png"  /> |

   You can click 'Send Config' and the Customer Display will move to Idle screen.

   |              Display Idle              |
   | :------------------------------------: |
   | <img src="images/Display Idle.png"  /> |

5. You are shown the following screen on Test POS Website.

   |              POS Send Promotions or Start Purchase              |
   | :-------------------------------------------------------------: |
   | <img src="images/POS Send Promotions or Start Purchase.png"  /> |

6. If you send promotions you can see the promotions on Customer Display application

   |              Display Promotions              |
   | :------------------------------------------: |
   | <img src="images/Display Promotions.png"  /> |

7. If you start purchase you will be moved to the active state where the purchase details of a customer can be displayed and they can also perform some actions on Customer Display application

   |             Display Purchase Started              |
   | :-----------------------------------------------: |
   | <img src="images/Display Active Purchase.png"  /> |

   Test POS Website shows you a set of actions that can be performed.

   |              POS Choose Action              |
   | :-----------------------------------------: |
   | <img src="images/POS Choose Action.png"  /> |

8. Now you can perform some actions that are needed.
   A few example actions that can be taken:

   - Set Products
     You'll be shown JSON that can be used to set product.

     |              POS Set Products              |
     | :----------------------------------------: |
     | <img src="images/POS Set Products.png"  /> |

     Once you click the 'Set Products', the products details will be sent to and displayed on Customer Display.

     |              Display Products Added              |
     | :----------------------------------------------: |
     | <img src="images/Display Products Added.png"  /> |

   - Get Tip
     You'll be shown JSON that can be used to Get Tip Info from Display.

     |              POS Get Tip              |
     | :-----------------------------------: |
     | <img src="images/POS Get Tip.png"  /> |

     Once you click the 'Get Tip', the form to get the tip will be displayed on Customer Display.

     |              Display Get Tip              |
     | :---------------------------------------: |
     | <img src="images/Display Get Tip.png"  /> |

     You can choose or enter the amount you want to tip and confirm the tip.

     |              Display Confirm Tip              |
     | :---------------------------------------: |
     | <img src="images/Display Confirm Tip.png"  /> |

     Once you confrim tip, the Customer Display will move into a state where it waits for Test POS website to confirm the same.

     |              Display Confirming Tip              |
     | :---------------------------------------: |
     | <img src="images/Display Confirming Tip.png"  /> |

     Test POS website is shown details of tip, that can be confirmed by choosing any one option

     |              POS Confirm Tip             |
     | :---------------------------------------: |
     | <img src="images/POS Confirm Tip.png"  /> |

     Here, we're choosing to send only the Tip, the following will be shown on Test POS Website.

     |              POS Send Only Tip             |
     | :---------------------------------------: |
     | <img src="images/POS Send Only Tip.png"  /> |

     This will complete the tip addition and show the details of tip on the Customer Display Applicatoin

     |              Display Tip Confirmed             |
     | :---------------------------------------: |
     | <img src="images/Display Tip Confirmed.png"  /> |

   - Complete Purchase
     You can complete purchase which will take the details needed from customer

     |              POS Complete Purchase              |
     | :-----------------------------------: |
     | <img src="images/POS Complete Purchase.png"  /> |

     |              Display Complete Purchase              |
     | :-----------------------------------: |
     | <img src="images/Display Complete Purchase.png"  /> |

   - Finish
     This will end the current purchase and move back to idle/promotions screen.

     |              Display Finish Purchase              |
     | :-----------------------------------: |
     | <img src="images/Display Finish Purchase.png"  /> |

9. You can repeat this process or end the connection.

That's it! Thank you for the time to go through the testing process.