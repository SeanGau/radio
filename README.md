# @makeform/radio

Fields:

 - `values`: array of string ( for available choices ).
 - `other`: user can input other reply.
   - `enabled`: true/false.
   - `prompt`: default `其他`/`Other`.


Example configuration:

    {   
      isRequired: true,
      config: {
        values: [
          "some description, for item1"
          "some other description, for item 2"
          "yet another description, for item 3"
        ]
        other:
          enabled: true
      }
    }
    
## License

MIT
