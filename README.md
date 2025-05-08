# Java-Course

\n  a Newline (or Return) character

\t  a Tab character

\"  a Double Quote mark. This is used to include a Double Quote mark as a character in a String literal. For example: we can encode the String: He said "Hello!"
as a String literal like this: "He said \"Hello!\""

\'   a Single Quote mark. For example, we can represent a Single Quote mark as a char literal like this:  '\'' Note that there are three single quote marks in the char literal.

=========Java reserved words / keywords.========

                    abstract
                    assert
                    boolean
                    break
                    byte
                    case
                    catch
                    char
                    class
                    const
                    continue
                    default
                    do
                    double
                    else
                    enum
                    extends	final
                    finally
                    float
                    for
                    goto
                    if
                    implements
                    import
                    instanceof
                    int
                    interface
                    long
                    native
                    new
                    package
                    private
                    protected	public
                    return
                    short
                    static
                    strictfp
                    super
                    switch
                    synchronized
                    this
                    throw
                    throws
                    transient
                    try
                    void
                    volatile
                    while

Precedence rules for arithmetic operators.

Operator/Convention

( )	Items within parentheses are evaluated first
In 2 * (x + 1), the x + 1 is evaluated first, then result is multiplied by 2

the unary minus operator (-) is used for negation. It has higher precedence than most binary operators, meaning it's evaluated before operations like multiplication or addition.

Multiplication, Division, Modulo (*, /, %) (Same Precedence)
Evaluated left-to-right when they appear together.
Example: 8 / 4 * 2 → (8 / 4) * 2 = 4.
Example: 10 % 3 * 2 → (10 % 3) * 2 = 2 * 2 = 4.

Addition & Subtraction (+, -) (Same Precedence, Lower than *, /, %)
Evaluated left-to-right when they appear together.
Example: 5 + 3 - 2 → (5 + 3) - 2 = 6.
Example: 3 + 2 * 4 → 3 + (2 * 4) = 11 (since * has higher precedence).

Key Rules
Higher precedence operators are evaluated first (*, /, % before +, -).
Left-to-right evaluation for operators of equal precedence.
Parentheses ( ) override precedence and force evaluation first.

Expression	            Evaluation Steps	          Result
2 + 3 * 4	            2 + (3 * 4) → 2 + 12	        14
8 / 2 * 3	            (8 / 2) * 3 → 4 * 3	            12
10 % 3 + 5	            (10 % 3) + 5 → 1 + 5	        6
6 * 3 / 2	            (6 * 3) / 2 → 18 / 2	        9
4 + 6 - 2 + 1	    (4 + 6) - 2 + 1 → 10 - 2 + 1 → 9	9

When in Doubt, Use Parentheses!
(2 + 3) * 4 → 5 * 4 = 20     (Different from 2 + 3 * 4 = 14)
10 % (3 + 2) → 10 % 5 = 0    (Different from 10 % 3 + 2 = 1 + 2 = 3)


Format Specifiers Summary
Specifier	                    Data Type(s)	                            Description
    %c	                             char	                  Prints a single Unicode character.
    %d	                        int, long, short	         Prints a decimal (base-10) integer.
    %o	                        int, long, short	            Prints an octal (base-8) integer.
    %x / %h	                int, char, long, short	        Prints a hexadecimal (base-16) integer (lowercase). Use %X for uppercase.
    %f	                        float, double	            Prints a floating-point number (decimal notation).
    %e / %E	                    float, double	            Prints a floating-point number in scientific notation (e.g., 1.23e+04).
    %s	                        String (or char[] in C)	    Prints a string of characters.
    %%	                                —	                Prints a literal % character (escape for %).
    %n	                                —	                Inserts a platform-specific newline.