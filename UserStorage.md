# User Storage & Authentication Guide
---
## 1. Create User entity
<details>
<summary><b>View Code: User.java</b></summary>
  '''java
  @Entity
public class User {
    @Id
    @GeneratedValue(strategy = GenerationType.IDENTITY)
    private Integer id;
    @Email
    private String email;
    private String password;
    private String authority;
  //Getters and Setters
  }
## 2. Create User interface extending CrudRepository
## 3. Create User Adapter class implementing UserDetails
## 4. Create UserDetails Service class implementing UserDetailsService
## 5. Create a SecurityConfig configuration
## 6. Add a "/register" POST endpoint to the controller 
