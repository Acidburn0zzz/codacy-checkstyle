Since Checkstyle 3.4

Checks the padding of an empty for initializer; that is whether white space is required at an empty for initializer, or such white space is forbidden. No check occurs if there is a line wrap at the initializer, as in

    for (
          ; i < j; i++, j--)