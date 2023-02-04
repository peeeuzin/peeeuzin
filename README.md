```

                    ___           ___           ___                        ___     
      ___          /  /\         /  /\         /__/\           ___        /  /\    
     /  /\        /  /::\       /  /:/         \  \:\         /__/\      /  /::|   
    /  /::\      /  /:/\:\     /  /:/           \  \:\        \__\:\    /  /:|:|   
   /  /:/\:\    /  /::\ \:\   /  /:/             \  \:\       /  /::\  /  /:/|:|__ 
  /  /::\ \:\  /__/:/\:\ \:\ /__/:/     /\  ______\__\:\   __/  /:/\/ /__/:/ |:| /\
 /__/:/\:\_\:\ \  \:\ \:\_\/ \  \:\    /:/ \  \::::::::/  /__/\/:/~~  \__\/  |:|/:/
 \__\/  \:\/:/  \  \:\ \:\    \  \:\  /:/   \  \:\~~~~~   \  \::/         |  |:/:/ 
      \  \::/    \  \:\_\/     \  \:\/:/     \  \:\        \  \:\         |__|::/  
       \__\/      \  \:\        \  \::/       \  \:\        \__\/         /__/:/   
                   \__\/         \__\/         \__\/                      \__\/    

```

```
~ $ peeeuzin location
['Brasilia', 'Brazil']
~ $ peeeuzin languages
['Portuguese', 'English']
~ $ cat peeeuzin.ts
const me = {
    name: 'Pedro Augusto',
    age: 16,
    location: ['Brasilia', 'Brazil'],
    languages: ['Portuguese', 'English'],
    skills: {
        languages: ['Typescript/Javascript', 'CSS', 'HTML', 'Elixir', 'C#', 'Rust', 'C++', 'C'],
        frameworks: ['React', 'Next.js', 'NestJS', 'Express'],
        databases: ['PostgreSQL', 'MongoDB', 'Redis', 'SQLite'],
        tools: ['Git', 'Docker', 'VSCode', 'Linux', 'Windows'],
    },
    
    getCurrentLearning: () => {
        return 'Zig';
    }
}

export default me;

~ $ npm publish
```
