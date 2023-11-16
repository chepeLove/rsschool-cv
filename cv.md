# **Ilya Chepelov**

## My Contact Info:

- Phone: +375 33 305-89-23
- E-mail: ilya.chepelov@gmail.com
- LinkedIn: [chepeLove](https://www.linkedin.com/in/chepelove/ "LinkedIn")
- GitHub: [chepeLove](https://github.com/chepeLove "GitHub")
- Telegram: [chepeLove](https://t.me/chepe1ove "Telegram")
- Instagram: [chepeLove](https://www.instagram.com/chp.luv/ "Instagram")

## About Me

I am a motivated and goal-oriented software developer with a focus on continuous learning and professional development.
My goal is to develop in the software development field and become actively involved in projects that will allow me to
apply and expand my skills.

## Tech Stack:

- React
- React Native
- JavaScript / TypeScript
- HTML, CSS
- Redux/ Redux Toolkit / MobX
- Node.js(base)
- MongoDB(base)
- Git/Github/Github Actions
- React-hook-form, Formik
- Storybook / loki

## Soft skills:
- Responsible, hardworking and interested in IT.
- Strong interpersonal and communication skills, able to work under pressure and handle multiple task,
  result and goal oriented, eager to work, attentive and easy learning.
- Easily find a common language with everyone.

## Code Examples

```
export const taskAPI = {
    getTasks(todolistId:string){
        return instance.get<TaskResponseType>(`todo-lists/${todolistId}/tasks`)
    },
    createTask(todolistId:string,title:string){
        return instance.post<ResponseType<{item:TaskType}>>(`todo-lists/${todolistId}/tasks`,{title})
    },
    deleteTask(todolistId:string,taskId:string){
        return instance.delete<ResponseType>(`todo-lists/${todolistId}/tasks/${taskId}`)
    },
    updateTask(todolistId:string,taskId:string,model:UpdateTaskType){
        return instance.put<ResponseType>(`todo-lists/${todolistId}/tasks/${taskId}`,model)
    }
}

```


## Experience
- IT-INCUBATOR: Front-End Development: _Internship and mentoring_
- On my [GitHub](https://github.com/chepeLove "GitHub") you can find the projects 'Social Network', 'Todolist' and 'Counter' made for the IT-Incubator company. As well as my own projects and freelance projects

## Education

Belarusian State Technological University

Engineer's degree,
Chemical technology of inorganic substances  
2016-2021

## Courses
- IT-INCUBATOR: Front-End Development: _Studying since July 2023_

## Languages

- Russian - native speaker
- English - A2+