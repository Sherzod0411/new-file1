# new-file1
    public static void main(String[] args) {

        Student student = new Student();

        Student student1 = new Student("Lucy");

        Student student2 = new Student("Lucy", 'W');

        Student student3 = new Student("Anvar", 'M', 18);

        Student student4 = new Student("Aziza", 'W', 19, 2);

        Student student5 = new Student("Halim", 'M', 20, 3, "Economy");

        Student student6 = new Student("Aziz", 'M', 22, 4, "Economy", "USA");

        String [] a= new String [10];

        Student [] b = new Student[7];

        b[0] = student;
        b[1] = student1;
        b[2] = student2;
        b[3] = student3;
        b[4] = student4;
        b[5] = student5;
        b[6] = student6;

        for(int i =0 ; i<b.length; i++)
        {
            Student s = b[i];
            System.out.println(s.fullName);
        }
    }
}
