# User Storage & Authentication Guide

---

## 1. Create User entity

<details>
<summary><b>View Code: User.java</b></summary>

```java
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
```

</details>

## 2. Create User interface extending CrudRepository

<details>
<summary><b>View Code</b></summary>

```java

```

</details>

## 3. Create User Adapter class implementing UserDetails

<details>
<summary><b>View Code</b></summary>

```java

```

</details>

## 4. Create UserDetails Service class implementing UserDetailsService

<details>
<summary><b>View Code</b></summary>

```java

```

</details>

## 5. Create a SecurityConfig configuration

<details>
<summary><b>View Code</b></summary>

```java

```

</details>

## 6. Add a "/register" POST endpoint to the controller

<details>
<summary><b>View Code</b></summary>

```java

```

</details>
