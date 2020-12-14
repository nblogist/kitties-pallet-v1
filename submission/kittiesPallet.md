Kitties Pallet Design
-
This is a design document submitted for substrate developer academy assignment 2

### Types
  * struct Kitties
    * mother: u128
    * father: u128
    * name: &str
    * dna: u128 = rnd.gen()
    * owner: AccountId

  * struct User
    * address: AccountId
    * kittiesOwner: Vec<u128>

### Calls
  * fn creatKitty() -> Kitty_Created(kittyDNA)
  * fn transferKitty(kittyDNA: u128, transferTo: AccountId) -> Kitty_Transfered(sender_address, reciever Address)

### Events
  * Kitty_Created(kittyDNA)
  * Kitty_Transfered(sender_address, reciever Address)
