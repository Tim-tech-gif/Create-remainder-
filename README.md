# Create-remainder-
fn gen_shipments(n: usize) -> Vec&lt;u32> {     // Створюємо вектор розміру 32, спочатку заповнений нулями     let mut shipments = vec![0u32; 32];      // Розраховуємо скільки одиниць припадає на кожен елемент     let base = (n / 32) as u32;     let remainder = (n % 32) as u32;
