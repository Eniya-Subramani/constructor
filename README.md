# constructor
Class Customer {
private String name;
private long accountNumber;
private double balance;
Customer(String name, long accountNumber, double balance) {
this.name = name;
this.accountNumber = accountNumber;
this.balance = balance;
}
public void displayDetails() {
System.out.println(&quot;Customer Name: &quot; + name);

System.out.println(&quot;Account Number: &quot; + accountNumber);
System.out.println(&quot;Account Balance: &quot; + balance);
}
public static void main(String[] args) {
Customer c1 = new Customer(&quot;Kaviya&quot;, 12345, 25000.35);
Customer c2 = new Customer(&quot;Ramya&quot;, 14356, 15000.60);
System.out.println(&quot;\n--- Customer 1 ---&quot;);
c1.displayDetails();
System.out.println(&quot;\n--- Customer 2 ---&quot;);
c2.displayDetails();
}
}
OUTPUT:
--- Customer 1 ---
Customer Name: Kaviya
Account Number: 12345
Account Balance: 25000.35
--- Customer 2 ---
Customer Name: Ramya
Account Number: 14356
Account Balance: 15000.6
