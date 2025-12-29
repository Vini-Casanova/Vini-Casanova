
```elixir
setup do
  developer = %{
    name: "Vinicius",
    location: "Brazil",
    skills: ["Elixir", "Java", "Javascript", "C#"],
    social = %{
      linkedin: "https://www.linkedin.com/in/vinicius-casanova-624716230/"
    }
  }

  [prefered_language | _ ] = developer.skills 
end
```

