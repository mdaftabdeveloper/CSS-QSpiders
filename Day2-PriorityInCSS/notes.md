# Priority of CSS

-> Priority of Inline CSS is very high.
-> Priority of External CSS is medium.
-> Priority of External CSS is very less.

# CSS Syntax:

1. Selection: Selection is used to targetthe html element so that we can apply the property.
2. Property: This is the property we want to apply on html element that we have targetted.
3. selection : {
   property:value;
   ...
   ...
   ...
   }
   -> Example:
   h1 {
   color:orange;
   }

# Types of Selectors

1. Simple Selector
2. Combination Selector
3. Pseudo Class Selector (:)
4. Pseudo Element Selector (::)
5. Attribute Selector

=> Simple Selector

1. Tagname/ Element Selector:
    tagname {
        property:value;
    }
2. Id Selector(#):
    #__________: {
        property:value
    }
3. Class Selector(.):
    .________ {
        property:value
    }
4. Universal/Wildcard Selector(*):
    * {
        property:value
    }
5. Grouping Selector(,):
    tagname, #______, ._______ {
        property:value;
    }

=> Priority in Simple Selector

1.! important
2. Id Selector(#)
3. Class Selector(.)
4. Tagname Selector
5. Universal/Wildcard Selector(*)
