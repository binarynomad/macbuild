# macbuild
Playing with automation scripts in a non-MDM environment


```mermaid
flowchard LR

DEP --|sends serials|--> MDM

MDM --|pushes profiles|-->Laptop

Laptop --|checks|--> Apple

Admin --|manages|--> DEP & MDM

```
