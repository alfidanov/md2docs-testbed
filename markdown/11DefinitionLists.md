**Syntax**


Definition Term
: Definition of above term
: Another definition of above term


Definitions terms can have no definitions if they are not the last term before a definition:

Definition Term without definition  
Definition Term  
: Definition of above term  
: Another definition of above term


A blank line between the definition term and definition, or the definition term and previous definition term will create a "loose" definition by wrapping its text in &lt;p&gt;&lt;/p&gt;

Definition Term

: Loose Definition of above term  
: Tight definition of above term

: Another loose definition term



Lazy continuation of definitions is supported and definition terms which follow a definition must be separated from it by a blank line.

Definition Term  
: Definition for Definition Term

Another Definition Term  
: Definition for Another Definition Term



Inline markdown is allowed in both terms and definitions. Definitions can contain any other markdown elements provided these are indented as per list indentation rules.

Multiple definition terms cannot be separated by blank lines since all but the last term will be treated as paragraph text:


Not a definition term.

Neither is this.

Definition Term
Another Definition Term

: Definition



Definition **Term
Another** Definition Term
: definition `item`