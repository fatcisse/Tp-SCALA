# Tp-SCALA
def pgcd(a: Int, b: Int): Int = {
  if (b == 0) a else pgcd(b, a % b)
}

pgcd(28,213)
pgcd(63,40)

def fibonacci(n: Int): Int = {
  if (n <= 1) n
  else fibonacci(n - 1) + fibonacci(n - 2)
}

fibonacci(0)
fibonacci(1)
