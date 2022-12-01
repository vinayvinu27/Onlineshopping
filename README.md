# Onlineshopping

import java.util.Scanner;

public class Demo1 {
    Scanner input = new Scanner(System.in);
    Scanner Input = new Scanner(System.in);
    Scanner NUM = new Scanner(System.in);
    Scanner Choose = new Scanner(System.in);
    Scanner Tshits = new Scanner(System.in);
    Scanner Woodies = new Scanner(System.in);
    Scanner order = new Scanner(System.in);
    Scanner order1 = new Scanner(System.in);
    Scanner Women = new Scanner(System.in);
    Scanner Tech = new Scanner(System.in);
    Scanner Accerses = new Scanner(System.in);
    Scanner Toys = new Scanner(System.in);
    Scanner Exit = new Scanner(System.in);
    Scanner Mac = new Scanner(System.in);
    Scanner Mobiles = new Scanner(System.in);
    //Scanner  = new Scanner(System.in);




    void menu(int sc)
    {
        int Menu = sc;
        if (Menu == 1)
        {
            System.out.println("101) Electonics");
            System.out.println("102) Fashion");
            System.out.println("103) Fruits,Vegetables & Grocery");
            System.out.println("104) clothes");
            System.out.println("105) clothes");
            System.out.println("106) Exit");
            //////////////////////////////////////////

            ///////////////////////////////////////////
            int Option = input.nextInt();
            switch (Option) {
                case 101:
                    System.out.println("1)Labtops");
                    System.out.println("2)Mobiles");
                    System.out.println("3) Return To Menu");
                    int intput = Input.nextInt();
                    if (intput == 1) {
                        switch (intput) {

                            case 1:
                                System.out.println("1) Mac");
                                System.out.println("2) Windows");
                                System.out.println("3) Return To Menu");
                                int mac = Mac.nextInt();
                                if (mac == 1) {
                                    switch (mac) {
                                        case 1:
                                            System.out.print("1)MacBool M1 Chip           ");
                                            System.out.println("2) MacBook Pro");
                                    }
                                    int Tshit = Tshits.nextInt();
                                    switch (Tshit) {
                                        case 1:
                                            System.out.println("Mac M1Chip");
                                            System.out.println("                Details");
                                            System.out.println("M1 chip processer & 8GB Ram & 256 GB SSd & 13.3 Inch Display");
                                            System.out.println("Are you want to Buy Pls conform");
                                            System.out.println("1) Yes & 2) No");
                                            int Order = order.nextInt();
                                            if (Order == 1) {
                                                System.out.println("Your Order is placed");
                                            } else if (Order == 2) {
                                                System.out.println("Ok Your Order is not placed");
                                            } else {
                                                System.out.println("Pls Enter Valid Number");
                                            }
                                            break;
                                        case 2:
                                            System.out.println("MacBool pro");
                                            System.out.println("                Details");
                                            System.out.println("M1 chip processer & 16GB Ram & 512 GB SSd & 13.3 Inch Display");
                                            System.out.println("Are you want to Buy Pls conform");
                                            System.out.println("1) Yes & 2) No");
                                            int Order2 = order.nextInt();
                                            if (Order2 == 1) {
                                                System.out.println("Your Order is placed");
                                            } else if (Order2 == 2) {
                                                System.out.println("Ok Your Order is not placed");
                                            } else {
                                                System.out.println("Pls Enter Valid Number");
                                            }
                                            break;

                                    }


                                } else if (mac == 2) {
                                    System.out.println("1) HP");
                                    System.out.println("2) DELL");
                                    System.out.println("3) ASUS");
                                    System.out.println("4) Return To Menu");
                                    int women = Women.nextInt();
                                    switch (women) {
                                        case 1:
                                            System.out.println("HP");
                                            System.out.println("               Details");
                                            System.out.println("HP pavilion i12 Core & 16GB Ram & 1TB SSD MRP=75,000/-");
                                            System.out.println("Are you want to Buy Pls conform");
                                            System.out.println("1) Yes & 2) No");
                                            int Order = order.nextInt();
                                            if (Order == 1) {
                                                System.out.println("Your Order is placed");
                                            } else if (Order == 2) {
                                                System.out.println("Ok Your Order is not placed");
                                            } else {
                                                System.out.println("Pls Enter Valid Number");
                                            }
                                            break;
                                        case 2:
                                            System.out.println("DELL");
                                            System.out.println("               Details");
                                            System.out.println("DELL Inspiron Core i5 11th Gen - (8 GB/512 GB SSD/Windows 11 Home) Inspiron 5410 2 in 1 Laptop  (14 Inch, Platinum Silver, 1.5 Kgs, With MS Office)" +
                                                    "₹72,490");
                                            System.out.println("Are you want to Buy Pls conform");
                                            System.out.println("1) Yes & 2) No");
                                            int Order2 = order.nextInt();
                                            if (Order2 == 1) {
                                                System.out.println("Your Order is placed");
                                            } else if (Order2 == 2) {
                                                System.out.println("Ok Your Order is not placed");
                                            } else {
                                                System.out.println("Pls Enter Valid Number");
                                            }
                                            break;
                                        case 3:
                                            System.out.println("ASUS");
                                            System.out.println("               Details");
                                            System.out.println("ASUS VivoBook 15 (2022) Core i5 11th Gen - (8 GB/1 TB HDD/256 GB SSD/Windows 11 Home) X515EA-EJ502WS Thin and Light Laptop  (15.6 inch, Transparent Silver, 1.80 kg, With MS Office)" +
                                                    "₹51,990");
                                            System.out.println("Are you want to Buy Pls conform");
                                            System.out.println("1) Yes & 2) No");
                                            int Order3 = order.nextInt();
                                            if (Order3 == 1) {
                                                System.out.println("Your Order is placed");
                                            } else if (Order3 == 2) {
                                                System.out.println("Ok Your Order is not placed");
                                            } else {
                                                System.out.println("Pls Enter Valid Number");
                                            }
                                            break;


                                    }
                                }
                        }
                    } else if (intput == 2) {
                        switch (intput) {
                            case 2:
                                System.out.println("1) Iphone");
                                System.out.println("2) Android");
                                int mobile = Mobiles.nextInt();
                                if (mobile==1)
                                {
                                    switch (mobile)
                                    {
                                        case 1:
                                            System.out.print("1)Iphone14 Pro Max          ");
                                            System.out.println("2)Iphone 13 Pro ");
                                    }
                                    int Tshit = Tshits.nextInt();
                                    switch (Tshit) {
                                        case 1:
                                            System.out.println("Iphone14 Pro Max ");
                                            System.out.println("                Details");
                                            System.out.println("M1 chip processer & 8GB Ram & 256 GB SSd & 13.3 Inch Display");
                                            System.out.println("Are you want to Buy Pls conform");
                                            System.out.println("1) Yes & 2) No");
                                            int Order = order.nextInt();
                                            if (Order == 1) {
                                                System.out.println("Your Order is placed");
                                            } else if (Order == 2) {
                                                System.out.println("Ok Your Order is not placed");
                                            } else {
                                                System.out.println("Pls Enter Valid Number");
                                            }
                                            break;
                                        case 2:
                                            System.out.println("Iphone 13 Pro");
                                            System.out.println("                Details");
                                            System.out.println("M1 chip processer & 16GB Ram & 512 GB SSd & 13.3 Inch Display");
                                            System.out.println("Are you want to Buy Pls conform");
                                            System.out.println("1) Yes & 2) No");
                                            int Order2 = order.nextInt();
                                            if (Order2 == 1) {
                                                System.out.println("Your Order is placed");
                                            } else if (Order2 == 2) {
                                                System.out.println("Ok Your Order is not placed");
                                            } else {
                                                System.out.println("Pls Enter Valid Number");
                                            }
                                            break;

                                    }
                                }
                                else if (mobile==2)
                                {
                                    System.out.print("1)OnePluse         ");
                                    System.out.println("2)Samsung ");
                                    switch (mobile)
                                    {
                                        case 1:
                                            System.out.print("1)OnePluse         ");
                                            System.out.println("2)Samsung ");
                                    }
                                    int Tshit = Tshits.nextInt();
                                    switch (Tshit) {
                                        case 1:
                                            System.out.println("OnePluse ");
                                            System.out.println("                Details");
                                            System.out.println("M1 chip processer & 8GB Ram & 256 GB SSd & 13.3 Inch Display");
                                            System.out.println("Are you want to Buy Pls conform");
                                            System.out.println("1) Yes & 2) No");
                                            int Order = order.nextInt();
                                            if (Order == 1) {
                                                System.out.println("Your Order is placed");
                                            } else if (Order == 2) {
                                                System.out.println("Ok Your Order is not placed");
                                            } else {
                                                System.out.println("Pls Enter Valid Number");
                                            }
                                            break;
                                        case 2:
                                            System.out.println("Samsung");
                                            System.out.println("                Details");
                                            System.out.println("M1 chip processer & 16GB Ram & 512 GB SSd & 13.3 Inch Display");
                                            System.out.println("Are you want to Buy Pls conform");
                                            System.out.println("1) Yes & 2) No");
                                            int Order2 = order.nextInt();
                                            if (Order2 == 1) {
                                                System.out.println("Your Order is placed");
                                            } else if (Order2 == 2) {
                                                System.out.println("Ok Your Order is not placed");
                                            } else {
                                                System.out.println("Pls Enter Valid Number");
                                            }
                                            break;

                                    }
                                }
                        }
            }break;


     ////////////////////////////////////////////////////////////////////////////////////////////////////                           ////////////////////////////
                             case 102:
                                 System.out.println("1)Men's");
                                 System.out.println("2)Women's");
                                 System.out.println("3) Return To Menu");
                                 int Cloths = Input.nextInt();
                                 if (Cloths == 1) {
                                     switch (Cloths) {

                                         case 1:
                                             System.out.println("1) T-shirt");
                                             System.out.println("2) Woodies");
                                             System.out.println("3) Return To Menu");
                                             int mac = Mac.nextInt();
                                             if (mac == 1) {
                                                 switch (mac) {
                                                     case 1:
                                                         System.out.print("1)Full T-shirt          ");
                                                         System.out.println("2)Half T-shirt");
                                                 }
                                                 int Tshit = Tshits.nextInt();
                                                 switch (Tshit) {
                                                     case 1:
                                                         System.out.println("Full T-shirt");
                                                         System.out.println("                Details");
                                                         System.out.println("M1 chip processer & 8GB Ram & 256 GB SSd & 13.3 Inch Display");
                                                         System.out.println("Are you want to Buy Pls conform");
                                                         System.out.println("1) Yes & 2) No");
                                                         int Order = order.nextInt();
                                                         if (Order == 1) {
                                                             System.out.println("Your Order is placed");
                                                         } else if (Order == 2) {
                                                             System.out.println("Ok Your Order is not placed");
                                                         } else {
                                                             System.out.println("Pls Enter Valid Number");
                                                         }
                                                         break;
                                                     case 2:
                                                         System.out.println("Half T-shirt");
                                                         System.out.println("                Details");
                                                         System.out.println("M1 chip processer & 16GB Ram & 512 GB SSd & 13.3 Inch Display");
                                                         System.out.println("Are you want to Buy Pls conform");
                                                         System.out.println("1) Yes & 2) No");
                                                         int Order2 = order.nextInt();
                                                         if (Order2 == 1) {
                                                             System.out.println("Your Order is placed");
                                                         } else if (Order2 == 2) {
                                                             System.out.println("Ok Your Order is not placed");
                                                         } else {
                                                             System.out.println("Pls Enter Valid Number");
                                                         }
                                                         break;

                                                 }


                                             } else if (mac == 2) {
                                                 System.out.println("1) Oversized Woodies");
                                                 System.out.println("2) Sleeveless woodies");
                                                 System.out.println("3) Jeans");
                                                 System.out.println("4) Return To Menu");
                                                 int women = Women.nextInt();
                                                 switch (women) {
                                                     case 1:
                                                         System.out.println("Oversized Woodies");
                                                         System.out.println("               Details");
                                                         System.out.println("HP pavilion i12 Core & 16GB Ram & 1TB SSD MRP=75,000/-");
                                                         System.out.println("Are you want to Buy Pls conform");
                                                         System.out.println("1) Yes & 2) No");
                                                         int Order = order.nextInt();
                                                         if (Order == 1) {
                                                             System.out.println("Your Order is placed");
                                                         } else if (Order == 2) {
                                                             System.out.println("Ok Your Order is not placed");
                                                         } else {
                                                             System.out.println("Pls Enter Valid Number");
                                                         }
                                                         break;
                                                     case 2:
                                                         System.out.println("Sleeveless woodies");
                                                         System.out.println("               Details");
                                                         System.out.println("DELL Inspiron Core i5 11th Gen - (8 GB/512 GB SSD/Windows 11 Home) Inspiron 5410 2 in 1 Laptop  (14 Inch, Platinum Silver, 1.5 Kgs, With MS Office)" +
                                                                 "₹72,490");
                                                         System.out.println("Are you want to Buy Pls conform");
                                                         System.out.println("1) Yes & 2) No");
                                                         int Order2 = order.nextInt();
                                                         if (Order2 == 1) {
                                                             System.out.println("Your Order is placed");
                                                         } else if (Order2 == 2) {
                                                             System.out.println("Ok Your Order is not placed");
                                                         } else {
                                                             System.out.println("Pls Enter Valid Number");
                                                         }
                                                         break;
                                                     case 3:
                                                         System.out.println("Jeans");
                                                         System.out.println("               Details");
                                                         System.out.println("ASUS VivoBook 15 (2022) Core i5 11th Gen - (8 GB/1 TB HDD/256 GB SSD/Windows 11 Home) X515EA-EJ502WS Thin and Light Laptop  (15.6 inch, Transparent Silver, 1.80 kg, With MS Office)" +
                                                                 "₹51,990");
                                                         System.out.println("Are you want to Buy Pls conform");
                                                         System.out.println("1) Yes & 2) No");
                                                         int Order3 = order.nextInt();
                                                         if (Order3 == 1) {
                                                             System.out.println("Your Order is placed");
                                                         } else if (Order3 == 2) {
                                                             System.out.println("Ok Your Order is not placed");
                                                         } else {
                                                             System.out.println("Pls Enter Valid Number");
                                                         }
                                                         break;


                                                 }
                                             }
                                     }
                                 } else if (Cloths == 2) {
                                     switch (Cloths) {
                                         case 2:
                                         case 1:
                                             System.out.println("1) T-shirt");
                                             System.out.println("2) Woodies");
                                             System.out.println("3) Return To Menu");
                                             int mac = Mac.nextInt();
                                             if (mac == 1) {
                                                 switch (mac) {
                                                     case 1:
                                                         System.out.print("1)Full T-shirt          ");
                                                         System.out.println("2)Half T-shirt");
                                                 }
                                                 int Tshit = Tshits.nextInt();
                                                 switch (Tshit) {
                                                     case 1:
                                                         System.out.println("Full T-shirt");
                                                         System.out.println("                Details");
                                                         System.out.println("M1 chip processer & 8GB Ram & 256 GB SSd & 13.3 Inch Display");
                                                         System.out.println("Are you want to Buy Pls conform");
                                                         System.out.println("1) Yes & 2) No");
                                                         int Order = order.nextInt();
                                                         if (Order == 1) {
                                                             System.out.println("Your Order is placed");
                                                         } else if (Order == 2) {
                                                             System.out.println("Ok Your Order is not placed");
                                                         } else {
                                                             System.out.println("Pls Enter Valid Number");
                                                         }
                                                         break;
                                                     case 2:
                                                         System.out.println("Half T-shirt");
                                                         System.out.println("                Details");
                                                         System.out.println("M1 chip processer & 16GB Ram & 512 GB SSd & 13.3 Inch Display");
                                                         System.out.println("Are you want to Buy Pls conform");
                                                         System.out.println("1) Yes & 2) No");
                                                         int Order2 = order.nextInt();
                                                         if (Order2 == 1) {
                                                             System.out.println("Your Order is placed");
                                                         } else if (Order2 == 2) {
                                                             System.out.println("Ok Your Order is not placed");
                                                         } else {
                                                             System.out.println("Pls Enter Valid Number");
                                                         }
                                                         break;

                                                 }


                                             } else if (mac == 2) {
                                                 System.out.println("1) Oversized Woodies");
                                                 System.out.println("2) Sleeveless woodies");
                                                 System.out.println("3) Jeans");
                                                 System.out.println("4) Return To Menu");
                                                 int women = Women.nextInt();
                                                 switch (women) {
                                                     case 1:
                                                         System.out.println("Oversized Woodies");
                                                         System.out.println("               Details");
                                                         System.out.println("HP pavilion i12 Core & 16GB Ram & 1TB SSD MRP=75,000/-");
                                                         System.out.println("Are you want to Buy Pls conform");
                                                         System.out.println("1) Yes & 2) No");
                                                         int Order = order.nextInt();
                                                         if (Order == 1) {
                                                             System.out.println("Your Order is placed");
                                                         } else if (Order == 2) {
                                                             System.out.println("Ok Your Order is not placed");
                                                         } else {
                                                             System.out.println("Pls Enter Valid Number");
                                                         }
                                                         break;
                                                     case 2:
                                                         System.out.println("Sleeveless woodies");
                                                         System.out.println("               Details");
                                                         System.out.println("DELL Inspiron Core i5 11th Gen - (8 GB/512 GB SSD/Windows 11 Home) Inspiron 5410 2 in 1 Laptop  (14 Inch, Platinum Silver, 1.5 Kgs, With MS Office)" +
                                                                 "₹72,490");
                                                         System.out.println("Are you want to Buy Pls conform");
                                                         System.out.println("1) Yes & 2) No");
                                                         int Order2 = order.nextInt();
                                                         if (Order2 == 1) {
                                                             System.out.println("Your Order is placed");
                                                         } else if (Order2 == 2) {
                                                             System.out.println("Ok Your Order is not placed");
                                                         } else {
                                                             System.out.println("Pls Enter Valid Number");
                                                         }
                                                         break;
                                                     case 3:
                                                         System.out.println("Jeans");
                                                         System.out.println("               Details");
                                                         System.out.println("ASUS VivoBook 15 (2022) Core i5 11th Gen - (8 GB/1 TB HDD/256 GB SSD/Windows 11 Home) X515EA-EJ502WS Thin and Light Laptop  (15.6 inch, Transparent Silver, 1.80 kg, With MS Office)" +
                                                                 "₹51,990");
                                                         System.out.println("Are you want to Buy Pls conform");
                                                         System.out.println("1) Yes & 2) No");
                                                         int Order3 = order.nextInt();
                                                         if (Order3 == 1) {
                                                             System.out.println("Your Order is placed");
                                                         } else if (Order3 == 2) {
                                                             System.out.println("Ok Your Order is not placed");
                                                         } else {
                                                             System.out.println("Pls Enter Valid Number");
                                                         }
                                                         break;


                                                 }
                                             }
                                     }
                                 }break;
///////////////////////////////////////////////////////////
                case 103:
                    System.out.println("1)Fruits & Vegetables");
                    System.out.println("2)Groceruy");
                    System.out.println("3) Return To Menu");
                    int Groceruy = Input.nextInt();
                    if (Groceruy == 1) {
                        switch (Groceruy) {

                            case 1:
                                System.out.println("1) Fruits");
                                System.out.println("2) Vegetables");
                                System.out.println("3) Return To Menu");
                                int mac = Mac.nextInt();
                                if (mac == 1) {
                                    switch (mac) {
                                        case 1:
                                            System.out.println("1)Mango");
                                            System.out.println("2)Apple");
                                            System.out.println("3)Banana");
                                            System.out.println("4)Pineapple");
                                            System.out.println("5)Papaya");
                                    }
                                    int Tshit = Tshits.nextInt();
                                    switch (Tshit) {
                                        case 1:
                                            System.out.println("Mango");
                                            System.out.println("                Details");
                                            System.out.println("M1 chip processer & 8GB Ram & 256 GB SSd & 13.3 Inch Display");
                                            System.out.println("Are you want to Buy Pls conform");
                                            System.out.println("1) Yes & 2) No");
                                            int Order = order.nextInt();
                                            if (Order == 1) {
                                                System.out.println("Your Order is placed");
                                            } else if (Order == 2) {
                                                System.out.println("Ok Your Order is not placed");
                                            } else {
                                                System.out.println("Pls Enter Valid Number");
                                            }
                                            break;
                                        case 2:
                                            System.out.println("Apple");
                                            System.out.println("                Details");
                                            System.out.println("M1 chip processer & 16GB Ram & 512 GB SSd & 13.3 Inch Display");
                                            System.out.println("Are you want to Buy Pls conform");
                                            System.out.println("1) Yes & 2) No");
                                            int Order2 = order.nextInt();
                                            if (Order2 == 1) {
                                                System.out.println("Your Order is placed");
                                            } else if (Order2 == 2) {
                                                System.out.println("Ok Your Order is not placed");
                                            } else {
                                                System.out.println("Pls Enter Valid Number");
                                            }
                                            break;
                                        case 3:
                                            System.out.println("Apple");
                                            System.out.println("                Details");
                                            System.out.println("M1 chip processer & 16GB Ram & 512 GB SSd & 13.3 Inch Display");
                                            System.out.println("Are you want to Buy Pls conform");
                                            System.out.println("1) Yes & 2) No");
                                            int Order3 = order.nextInt();
                                            if (Order3 == 1) {
                                                System.out.println("Your Order is placed");
                                            } else if (Order3 == 2) {
                                                System.out.println("Ok Your Order is not placed");
                                            } else {
                                                System.out.println("Pls Enter Valid Number");
                                            }
                                            break;
                                        case 4:
                                            System.out.println("Apple");
                                            System.out.println("                Details");
                                            System.out.println("M1 chip processer & 16GB Ram & 512 GB SSd & 13.3 Inch Display");
                                            System.out.println("Are you want to Buy Pls conform");
                                            System.out.println("1) Yes & 2) No");
                                            int Order4 = order.nextInt();
                                            if (Order4 == 1) {
                                                System.out.println("Your Order is placed");
                                            } else if (Order4 == 2) {
                                                System.out.println("Ok Your Order is not placed");
                                            } else {
                                                System.out.println("Pls Enter Valid Number");
                                            }
                                            break;
                                        case 5:
                                            System.out.println("Apple");
                                            System.out.println("                Details");
                                            System.out.println("M1 chip processer & 16GB Ram & 512 GB SSd & 13.3 Inch Display");
                                            System.out.println("Are you want to Buy Pls conform");
                                            System.out.println("1) Yes & 2) No");
                                            int Order5 = order.nextInt();
                                            if (Order5 == 1) {
                                                System.out.println("Your Order is placed");
                                            } else if (Order5 == 2) {
                                                System.out.println("Ok Your Order is not placed");
                                            } else {
                                                System.out.println("Pls Enter Valid Number");
                                            }
                                            break;

                                    }


                                } else if (mac == 2) {
                                    System.out.println("1) Oversized Woodies");
                                    System.out.println("2) Sleeveless woodies");
                                    System.out.println("3) Jeans");
                                    System.out.println("4) Return To Menu");
                                    int women = Women.nextInt();
                                    switch (women) {
                                        case 1:
                                            System.out.println("Oversized Woodies");
                                            System.out.println("               Details");
                                            System.out.println("HP pavilion i12 Core & 16GB Ram & 1TB SSD MRP=75,000/-");
                                            System.out.println("Are you want to Buy Pls conform");
                                            System.out.println("1) Yes & 2) No");
                                            int Order = order.nextInt();
                                            if (Order == 1) {
                                                System.out.println("Your Order is placed");
                                            } else if (Order == 2) {
                                                System.out.println("Ok Your Order is not placed");
                                            } else {
                                                System.out.println("Pls Enter Valid Number");
                                            }
                                            break;
                                        case 2:
                                            System.out.println("Sleeveless woodies");
                                            System.out.println("               Details");
                                            System.out.println("DELL Inspiron Core i5 11th Gen - (8 GB/512 GB SSD/Windows 11 Home) Inspiron 5410 2 in 1 Laptop  (14 Inch, Platinum Silver, 1.5 Kgs, With MS Office)" +
                                                    "₹72,490");
                                            System.out.println("Are you want to Buy Pls conform");
                                            System.out.println("1) Yes & 2) No");
                                            int Order2 = order.nextInt();
                                            if (Order2 == 1) {
                                                System.out.println("Your Order is placed");
                                            } else if (Order2 == 2) {
                                                System.out.println("Ok Your Order is not placed");
                                            } else {
                                                System.out.println("Pls Enter Valid Number");
                                            }
                                            break;
                                        case 3:
                                            System.out.println("Jeans");
                                            System.out.println("               Details");
                                            System.out.println("ASUS VivoBook 15 (2022) Core i5 11th Gen - (8 GB/1 TB HDD/256 GB SSD/Windows 11 Home) X515EA-EJ502WS Thin and Light Laptop  (15.6 inch, Transparent Silver, 1.80 kg, With MS Office)" +
                                                    "₹51,990");
                                            System.out.println("Are you want to Buy Pls conform");
                                            System.out.println("1) Yes & 2) No");
                                            int Order3 = order.nextInt();
                                            if (Order3 == 1) {
                                                System.out.println("Your Order is placed");
                                            } else if (Order3 == 2) {
                                                System.out.println("Ok Your Order is not placed");
                                            } else {
                                                System.out.println("Pls Enter Valid Number");
                                            }
                                            break;


                                    }
                                }
                        }
                    } else if (Groceruy == 2) {
                        switch (Groceruy) {
                            case 2:
                            case 1:
                                System.out.println("1) T-shirt");
                                System.out.println("2) Woodies");
                                System.out.println("3) Return To Menu");
                                int mac = Mac.nextInt();
                                if (mac == 1) {
                                    switch (mac) {
                                        case 1:
                                            System.out.print("1)Full T-shirt          ");
                                            System.out.println("2)Half T-shirt");
                                    }
                                    int Tshit = Tshits.nextInt();
                                    switch (Tshit) {
                                        case 1:
                                            System.out.println("Full T-shirt");
                                            System.out.println("                Details");
                                            System.out.println("M1 chip processer & 8GB Ram & 256 GB SSd & 13.3 Inch Display");
                                            System.out.println("Are you want to Buy Pls conform");
                                            System.out.println("1) Yes & 2) No");
                                            int Order = order.nextInt();
                                            if (Order == 1) {
                                                System.out.println("Your Order is placed");
                                            } else if (Order == 2) {
                                                System.out.println("Ok Your Order is not placed");
                                            } else {
                                                System.out.println("Pls Enter Valid Number");
                                            }
                                            break;
                                        case 2:
                                            System.out.println("Half T-shirt");
                                            System.out.println("                Details");
                                            System.out.println("M1 chip processer & 16GB Ram & 512 GB SSd & 13.3 Inch Display");
                                            System.out.println("Are you want to Buy Pls conform");
                                            System.out.println("1) Yes & 2) No");
                                            int Order2 = order.nextInt();
                                            if (Order2 == 1) {
                                                System.out.println("Your Order is placed");
                                            } else if (Order2 == 2) {
                                                System.out.println("Ok Your Order is not placed");
                                            } else {
                                                System.out.println("Pls Enter Valid Number");
                                            }
                                            break;

                                    }


                                } else if (mac == 2) {
                                    System.out.println("1) Oversized Woodies");
                                    System.out.println("2) Sleeveless woodies");
                                    System.out.println("3) Jeans");
                                    System.out.println("4) Return To Menu");
                                    int women = Women.nextInt();
                                    switch (women) {
                                        case 1:
                                            System.out.println("Oversized Woodies");
                                            System.out.println("               Details");
                                            System.out.println("HP pavilion i12 Core & 16GB Ram & 1TB SSD MRP=75,000/-");
                                            System.out.println("Are you want to Buy Pls conform");
                                            System.out.println("1) Yes & 2) No");
                                            int Order = order.nextInt();
                                            if (Order == 1) {
                                                System.out.println("Your Order is placed");
                                            } else if (Order == 2) {
                                                System.out.println("Ok Your Order is not placed");
                                            } else {
                                                System.out.println("Pls Enter Valid Number");
                                            }
                                            break;
                                        case 2:
                                            System.out.println("Sleeveless woodies");
                                            System.out.println("               Details");
                                            System.out.println("DELL Inspiron Core i5 11th Gen - (8 GB/512 GB SSD/Windows 11 Home) Inspiron 5410 2 in 1 Laptop  (14 Inch, Platinum Silver, 1.5 Kgs, With MS Office)" +
                                                    "₹72,490");
                                            System.out.println("Are you want to Buy Pls conform");
                                            System.out.println("1) Yes & 2) No");
                                            int Order2 = order.nextInt();
                                            if (Order2 == 1) {
                                                System.out.println("Your Order is placed");
                                            } else if (Order2 == 2) {
                                                System.out.println("Ok Your Order is not placed");
                                            } else {
                                                System.out.println("Pls Enter Valid Number");
                                            }
                                            break;
                                        case 3:
                                            System.out.println("Jeans");
                                            System.out.println("               Details");
                                            System.out.println("ASUS VivoBook 15 (2022) Core i5 11th Gen - (8 GB/1 TB HDD/256 GB SSD/Windows 11 Home) X515EA-EJ502WS Thin and Light Laptop  (15.6 inch, Transparent Silver, 1.80 kg, With MS Office)" +
                                                    "₹51,990");
                                            System.out.println("Are you want to Buy Pls conform");
                                            System.out.println("1) Yes & 2) No");
                                            int Order3 = order.nextInt();
                                            if (Order3 == 1) {
                                                System.out.println("Your Order is placed");
                                            } else if (Order3 == 2) {
                                                System.out.println("Ok Your Order is not placed");
                                            } else {
                                                System.out.println("Pls Enter Valid Number");
                                            }
                                            break;


                                    }
                                }
                        }
                    }break;
                    ////////////////////////////////////////////////////////////
                case 104:
                    System.out.println("1)Mens");
                    System.out.println("2)Womans");
                    System.out.println("3) Return To Menu");
                    int toys = Toys.nextInt();
                    if (toys == 1) {
                        switch (toys) {
                            case 1:
                                System.out.println("1) Half_T-shits");
                                System.out.println("2) Full_T-shits");
                                System.out.println("3) Return To Menu");
                                int Tshit = Tshits.nextInt();
                                switch (Tshit) {
                                    case 1:
                                        System.out.println("Half_T-shits");
                                        System.out.println("Are you want to Buy Pls conform");
                                        System.out.println("1) Yes & 2) No");
                                        int Order = order.nextInt();
                                        if (Order == 1) {
                                            System.out.println("Your Order is placed");
                                        } else if (Order == 2) {
                                            System.out.println("Ok Your Order is not placed");
                                        } else {
                                            System.out.println("Pls Enter Valid Number");
                                        }
                                        break;
                                    case 2:
                                        System.out.println("Full_T-shits");
                                        System.out.println("Are you want to Buy Pls conform");
                                        System.out.println("1) Yes & 2) No");
                                        int Order2 = order.nextInt();
                                        if (Order2 == 1) {
                                            System.out.println("Your Order is placed");
                                        } else if (Order2 == 2) {
                                            System.out.println("Ok Your Order is not placed");
                                        } else {
                                            System.out.println("Pls Enter Valid Number");
                                        }
                                        break;
                                    case 3:
                                        new Demo1().menu(sc);
                                }

                        }
                        new Demo1().menu(sc);


                    } else if (toys == 2) {
                        System.out.println("1) Half_T-shits");
                        System.out.println("2) Full_T-shits");
                        System.out.println("3) Return To Menu");
                        int women = Women.nextInt();
                        switch (women) {
                            case 1:
                                System.out.println("Half_T-shits");
                                System.out.println("Are you want to Buy Pls conform");
                                System.out.println("1) Yes & 2) No");
                                int Order = order.nextInt();
                                if (Order == 1) {
                                    System.out.println("Your Order is placed");
                                } else if (Order == 2) {
                                    System.out.println("Ok Your Order is not placed");
                                } else {
                                    System.out.println("Pls Enter Valid Number");
                                }
                                break;
                            case 2:
                                System.out.println("Full_T-shits");
                                System.out.println("Are you want to Buy Pls conform");
                                System.out.println("1) Yes & 2) No");
                                int Order2 = order.nextInt();
                                if (Order2 == 1) {
                                    System.out.println("Your Order is placed");
                                } else if (Order2 == 2) {
                                    System.out.println("Ok Your Order is not placed");
                                } else {
                                    System.out.println("Pls Enter Valid Number");
                                }
                                break;
                            case 3:
                                new Demo1().menu(sc);
                        }
                    }
                    new Demo1().menu(sc);
                    ///////////////////////////////////////////
                case 106:
                    return;
            }
            }


        }







    public static void main (String[]args){
               Scanner sc=new Scanner(System.in);
            System.out.println("(:─────────────────────────────────────────────────────:)");
            System.out.println("          Welcome to Daily Freesh Market Menu");
            System.out.println("      ▄▀▄ Welcome to online shopping    ▄▀▄▀ ");
            System.out.println("(:─────────────────────────────────────────────────────:)");

            System.out.println("                    1)Menu");
            System.out.println("                    0)Exit");
        new Demo1().menu(sc.nextInt());
        System.out.println("(:─────────────────────────────────────────────────────:)");
        System.out.println("          Welcome to Daily Freesh Market Menu");
        System.out.println("      ▄▀▄ Welcome to online shopping    ▄▀▄▀ ");
        System.out.println("(:─────────────────────────────────────────────────────:)");
            System.out.println("                    1)Menu");
            System.out.println("                    0)Exit");
        new Demo1().menu(sc.nextInt());
        }
    }

