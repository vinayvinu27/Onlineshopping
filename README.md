
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
    Scanner OtherItem = new Scanner(System.in);
    Scanner Mattress = new Scanner(System.in);

    void menu(int sc) {
        int Menu = sc;
        if (Menu == 1) {
            System.out.println("\n"+ "========================================================================\n" +
                    "[X1]\n" +
                    "-------------------THE ASCII ART FAQ TEN COMMANDMENTS-------------------"+"\n");
            System.out.println("\n" +
                    "                  \\\\\\\\`///\n" +
                    "                  /  _  _|                  \n" +
                    "                 (\\'('\\/')                  \n" +
                    "           ______/(    >(__                    \n" +
                    "          /`-    \\ \\_=__| `\\                \n" +
                    "         /       /__(  _____\\  _____            \n" +
                    "        /_ \\.____    ,\"     \".\"     \",__    \n" +
                    "       |    /   _\\__/_---------------/  \\   \n" +
                    "       \\/      /____  \\    MENU      ///        \n" +
                    "        )     / /   \\__\\--------------|          \n" +
                    "        '-.__|_/    ///    Electonics |          \n" +
                    "             \\_     |        |        |          \n" +
                    "               |    |      Fashion    |          101) Electonics\n" +
                    "                \\   |        |        |          102) Fashion\n" +
                    "                /   |Fruits,Veg,Grocery|         103) Fruits,Vegetables & Grocery\n" +
                    "                \\   |        |        |          104) OtherItems\n" +
                    "                 \\_ |      OtherItems |          105) Exit\n" +
                    "                   \\|        |        |         \n" +
                    "                    |       Exit     |    \n" +
                    "                    |________________|\n");
            System.out.println("\n"+ "========================================================================\n" +
                    "[X1]\n" +
                    "-------------------THE ASCII ART FAQ TEN COMMANDMENTS-------------------"+"\n");
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
                                if (mobile == 1) {
                                    switch (mobile) {
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
                                } else if (mobile == 2) {
                                    System.out.print("1)OnePluse         ");
                                    System.out.println("2)Samsung ");
                                    switch (mobile) {
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
                    }
                   new Demo1().menu(sc);


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
                    }
                    new Demo1().menu(sc);
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
                                            System.out.println("106) Return");
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
                                            System.out.println("Banana");
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
                                            System.out.println("Pineapple");
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
                                            System.out.println("Papaya");
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
                                    System.out.println("1) Tomato");
                                    System.out.println("2) Cucumber");
                                    System.out.println("3) Pumpkin");
                                    System.out.println("4) Onion");
                                    System.out.println("5) Carrots");
                                    System.out.println("106) Return to Menu");
                                    int women = Women.nextInt();
                                    switch (women) {
                                        case 1:
                                            System.out.println("Tomato");
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
                                            System.out.println("Cucumber");
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
                                            System.out.println("Pumpkin");
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
                                        case 4:
                                            System.out.println("Onion");
                                            System.out.println("               Details");
                                            System.out.println("ASUS VivoBook 15 (2022) Core i5 11th Gen - (8 GB/1 TB HDD/256 GB SSD/Windows 11 Home) X515EA-EJ502WS Thin and Light Laptop  (15.6 inch, Transparent Silver, 1.80 kg, With MS Office)" +
                                                    "₹51,990");
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
                                            System.out.println("Carrots");
                                            System.out.println("               Details");
                                            System.out.println("ASUS VivoBook 15 (2022) Core i5 11th Gen - (8 GB/1 TB HDD/256 GB SSD/Windows 11 Home) X515EA-EJ502WS Thin and Light Laptop  (15.6 inch, Transparent Silver, 1.80 kg, With MS Office)" +
                                                    "₹51,990");
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
                                }
                        }
                    } else if (Groceruy == 2) {
                        switch (Groceruy) {
                            case 2:
                            case 1:
                                System.out.println("1) Bread");
                                System.out.println("2) Meat ");
                                System.out.println("3) Rice ");
                                System.out.println("4) Cereals  ");
                                System.out.println("5) Cheese ");
                                System.out.println("106) Return To Menu");
                                int Tshit = Tshits.nextInt();
                                switch (Tshit) {
                                    case 1:
                                        System.out.println("Bread");
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
                                        System.out.println("Meat");
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
                                        System.out.println("Rice");
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
                                        System.out.println("CerealsCereals");
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
                                        System.out.println("Cheese");
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
                        }
                    }
                    new Demo1().menu(sc);
                    ////////////////////////////////////////////////////////////
                case 104:
                    System.out.println("1)OtherItems");
                    System.out.println("2)Return To Menu");

                    int Items = OtherItem.nextInt();
                    if (Items == 1) {
                        switch (Items) {
                            case 1:
                                System.out.println("1) GymItems");
                                System.out.println("2) Toys");
                                System.out.println("3) Home Appliances");
                                System.out.println("106) Return To Menu");
                                int mac = Mobiles.nextInt();
                                if (mac == 1) {
                                    switch (mac) {
                                        case 1:
                                            System.out.println("1)Limited GymItems       ");
                                            System.out.println("2)Full_GymItems");
                                    }
                                    int Tshit = Tshits.nextInt();
                                    switch (Tshit) {
                                        case 1:
                                            System.out.println("Limited GymItems");
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
                                            System.out.println("Full_GymItems");
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
                                    System.out.println("1) Boys_Toys");
                                    System.out.println("2) Girls-Toys");
                                    System.out.println("3) Return To Menu");
                                    int women = Women.nextInt();
                                    switch (women) {
                                        case 1:
                                            System.out.println("Boys_Toys");
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
                                            System.out.println("Girls-Toys");
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
                                } else if (mac == 3) {
                                    System.out.println("1) Mattress");
                                    System.out.println("2) Return To Menu");
                                    int mattress = Mattress.nextInt();
                                    if (mattress == 1) {
                                        switch (mattress) {
                                            case 1:
                                                System.out.println("1)Limited GymItems       ");
                                                System.out.println("2)Full_GymItems");
                                        }
                                        int women = Women.nextInt();
                                        switch (women) {
                                            case 1:
                                                System.out.println("Double Mattress");
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
                                                System.out.println("Single_Mattress");
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
                                new Demo1().menu(sc);
                                ///////////////////////////////////////////
                            case 105:
                                return;
                        }
                    }



            }
        }
    }






    public static void main (String[]args){
               Scanner sc=new Scanner(System.in);
        System.out.println("\n" +
                "\n" +"==========================================================================" +"\n"+
                "╦ ╦┌─┐┬  ┌─┐┌─┐┌┬┐┌─┐   ┌┬┐┌─┐   ╔═╗┌┐┌┬  ┬┌┐┌┌─┐   ╔═╗┬ ┬┌─┐┌─┐┌─┐┬┌┐┌┌─┐\n" +
                "║║║├┤ │  │  │ ││││├┤     │ │ │   ║ ║││││  ││││├┤    ╚═╗├─┤│ │├─┘├─┘│││││ ┬\n" +
                "╚╩╝└─┘┴─┘└─┘└─┘┴ ┴└─┘    ┴ └─┘   ╚═╝┘└┘┴─┘┴┘└┘└─┘   ╚═╝┴ ┴└─┘┴  ┴  ┴┘└┘└─┘\n"+
                "\n"+"============================================================================"+"\n"
        );

            System.out.println("                                  1)Menu");
            System.out.println("                                  0)Exit");
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

