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
    age: 17,
    location: ['Brasilia', 'Brazil'],
    languages: ['Portuguese', 'English'],
    skills: {
        languages: ['Typescript/Javascript', 'Rust', 'CSS', 'HTML', 'Elixir', 'C#', 'Java', 'Python', 'C++', 'C'],
        frameworks: ['React', 'React Native', 'Next.js', 'NestJS', 'Express', 'Django'],
        databases: ['PostgreSQL', 'MongoDB', 'Redis', 'SQLite'],
        tools: ['Git', 'Docker', 'VSCode', 'Linux', 'Windows', 'MacOS'],
    },
    
    getCurrentLearning: () => {
        return 'Tensorflow';
    }
}

export default me;

~ $ npm publish
```
