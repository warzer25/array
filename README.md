# array

            //--------------------------------------------------------------//
            ////part-1

            //int[] myarray = new int[3];

            //myarray[0] = 1;
            //myarray[1] = 2;
            //myarray[2] = 3;


            //Console.WriteLine(myarray[2]);
            //Console.ReadLine();

            //--------------------------------------------------------------//

            //int[] myarray1 = new int[3] { 5, 4, 6 };
            //                          //( 0, 1, 2 )

            //int[] myarray2 = new int[] { 5, 4, 6 };
            //                         //( 0, 1, 2 )

            //int[] myarray3 = { 5, 4, 6 };
            //               //( 0, 1, 2 )

            //Console.WriteLine(myarray3[1]);
            //Console.ReadLine();

            //-------------//---------------//----------------//------------------//
            ////part-2

            //int[] grades = { 66, 88, 95, 90, 100 };

            //for (int i=0; i<grades.Length ; i++)
            //{
            //    grades[i] += 3;
            //    Console.WriteLine(grades[i]);
            //}

            //Console.ReadLine();

            //--------------------------------------------------------------//

            //int[] grades = { 66, 88, 95, 90, 100 };

            //for (int i = grades.Length -1 ; i >=0; i--)
            //{
            //    grades[i] += 3;
            //    Console.WriteLine(grades[i]);
            //}

            //Console.ReadLine();

            //--------------------------------------------------------------//

            //int[] grades = { 66, 88, 95, 90, 100 };


            //      //(int name  in name of array) 
            //foreach (int score in grades)
            //{
            //    Console.WriteLine(score);
            //}

            //Console.ReadLine();

            //--------------------------------------------------------------//
            ////part-3
            ////check in class

            //string[] students = {"bob","jack","tom","ted"};

            //Console.WriteLine("enter student nmae for serch");
            //string studentname = Console.ReadLine();


            //bool contains = false;

            //for (int i = 0; i < students.Length; i++)
            //{
            //    if (studentname == students[i])
            //    {
            //        contains = true;
            //        break;
            //    }
            //    //with no breack
            //    //Console.WriteLine("number of run");
            //}
            //if (contains == true)
            //{
            //    Console.WriteLine("in class");

            //}
            //else
            //{
            //    Console.WriteLine("not in class");
            //}
            //Console.ReadLine();

            //--------------------------------------------------------------//
            ////check in class+grade

            //string[] students = { "bob", "jack", "tom", "ted" };
            //int[] grade =       { 77, 66, 88, 99 };

            //Console.WriteLine("enter student nmae for serch");
            //string studentname = Console.ReadLine();


            //bool contains = false;
            //int studentgrade=0;
            //for (int i = 0; i < students.Length; i++)
            //{
            //    if (studentname == students[i])
            //    {
            //        contains = true;
            //        studentgrade = grade[i];
            //        break;
            //    }
            //}
            //if (contains == true)
            //{
            //    Console.WriteLine("in class");
            //    Console.WriteLine("grade:{0}", studentgrade);
            //}
            //else
            //{
            //    Console.WriteLine("not in class");
            //}
            //Console.ReadLine();

            //---------//----------//-----------------//----------//---------//-------//
            ////part-4

            //int[] myarray = { 10, 15, 20, 30, 35, 40 ,45};

            //Console.WriteLine("check for number");
            //int number = int.Parse(Console.ReadLine());

            ////what we use to serch type binery must be sorted
            //int answer = Array.BinarySearch(myarray, number);

            //if (answer<0)
            //{
            //    Console.WriteLine("dont exsit");
            //}    
            //else
            //{
            //    Console.WriteLine("the number place in array {0}",answer);
            //}
            //Console.ReadLine();

            //---------------------------------------------------------------------//

            ////Sort

            //int[] myarray = { 15, 320, 130, 35, 440, 45 };

            //Array.Sort(myarray);
            //for (int i=0; i<myarray.Length;i++)
            //{
            //    Console.WriteLine(myarray[i]);
            //}
            //Console.ReadLine();

            ////Sort+Reverse

            //int[] myarray = { 15, 320, 130, 35, 440, 45 };

            //Array.Sort(myarray);
            //Array.Reverse(myarray);

            //for (int i = 0; i < myarray.Length; i++)
            //{
            //    Console.WriteLine(myarray[i]);
            //}
            //Console.ReadLine();

            //---------//----------//-----------------//----------//---------//-------//
            ////part-5

            ////[,] 2d array
            ////[,,] 3d array

            //                      //[y,x]      
            //int[,] myarray = new int[3,4];
            //                       //****
            //                       //****
            //     //[y,x]           //****
            //myarray[0, 0]= 99;
            //myarray[0, 1] = 2;
            //myarray[0, 2] = 3;
            //myarray[0, 3] = 4;

            //myarray[1, 0] = 40;
            //myarray[1, 1] = 3;
            //myarray[1, 2] = 2;
            //myarray[1, 3] = 1;

            //myarray[2, 0] = 2;
            //myarray[2, 1] = 2;
            //myarray[2, 2] = 4;
            //myarray[2, 3] = 4;

            //for (int i=0; i<3;i++)
            //{
            //    Console.WriteLine("");
            //    for (int j = 0; j < 4; j++)
            //    {
            //        Console.Write("{0,4}",myarray[i,j]);

            //    }
            //    Console.WriteLine("");
            //}

            //Console.ReadLine();

            //---------------------------------------------------------------------//
            //short hand

            //int[,] myA = {{5,6,7,8},
            //             { 5,6,7,8},
            //             { 5,6,7,8}};

            //---------------------------------------------------------------------//
            ////jacged array


            //int[][] myarray = new int[3][];

            //myarray[0] = new int[4] {5,6,7,8};
            //myarray[1] = new int[5] { 5, 6, 7, 8,9 };
            //myarray[2] = new int[6] { 4,5, 6, 7, 8,9};

            //for (int i = 0; i < 3; i++)
            //{
            //    Console.WriteLine("");
            //    for (int j = 0; j < myarray[i].Length; j++)
            //    {
            //        Console.Write("{0,4}", myarray[i][j]);

            //    }
            //    Console.WriteLine("");
            //}
            //Console.ReadLine();

            //---------------------------------------------------------------------//
