// tsconfig.json example TypeScript file

// This is a simple example of a TypeScript file that could be used in a project
// with a `tsconfig.json` configuration file.

interface User {
    id: number;
    name: string;
    email: string;
}

class UserService {
    private users: User[] = [];

    addUser(user: User): void {
        this.users.push(user);
    }

    getUserById(id: number): User | undefined {
        return this.users.find(user => user.id === id);
    }

    getAllUsers(): User[] {
        return this.users;
    }
}

// Example usage
const userService = new UserService();
userService.addUser({ id: 1, name: 'John Doe', email: 'john.doe@example.com' });
userService.addUser({ id: 2, name: 'Jane Smith', email: 'jane.smith@example.com' });

console.log(userService.getUserById(1));
console.log(userService.getAllUsers());
