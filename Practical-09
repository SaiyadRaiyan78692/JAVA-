class Rectangle {

    double width = 1;
    double height = 1;

    Rectangle() {
    }

    Rectangle(double width, double height) {
        this.width = width;
        this.height = height;
    }

    double getArea() {
        return width * height;
    }

    double getPerimeter() {
        return 2 * (width + height);
    }

    public static void main(String[] args) {

        if (args.length < 2) {
            System.out.println("Please provide width and height");
            return;
        }

        double w = Double.parseDouble(args[0]);
        double h = Double.parseDouble(args[1]);

        Rectangle r1 = new Rectangle(w, h);

        System.out.println("Rectangle 1:");
        System.out.println("Width = " + r1.width);
        System.out.println("Height = " + r1.height);
        System.out.println("Area = " + r1.getArea());
        System.out.println("Perimeter = " + r1.getPerimeter());
    }
}
