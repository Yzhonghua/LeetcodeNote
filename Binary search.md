- - [a, b]➡while(left <= right), cause the 'left == right' situation is meaningful. When exit, 'left == right + 1'.

    if we want floor(num), return right;

    if we want ceil(num), return left;

  - [a, b)➡while(left < right). When exit, 'left == right'.

  