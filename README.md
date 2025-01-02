# daily-planner
Daily Planner is an application that includes features such as task management, assignment tracking, a calendar view, to-do lists, and reminder notifications. The planner will allow users to manage their daily schedule, track assignments, and receive notifications for important deadlines.

Environment Setup Process: 
1. Installed React Native CLI (0.76.5) with: npx react-native init DailyPlannerApp
2. Installed Cocoa Pods: sudo gem install cocoa pods
3. Install Required dependencies: npm install @react-navigation/native @react-navigation/stack react-native-firebase/app react-native-firebase/auth react-native-firebase/messaging react-native-paper. To do this, authenticate via SSH to access the GitHub repository:
   - Check if an SSH Key is Configured: ls -al ~/.ssh
   - Generate an SSH Key (if needed): ssh-keygen -t rsa -b 4096 -C "olgabienzobas02@gmail.com"
   - Add Your SSH Key to the SSH Agent: eval "$(ssh-agent -s)"
                                               ssh-add ~/.ssh/id_rsa
   - Copy the SSH Key to Clipboard: pbcopy < ~/.ssh/id_rsa.pub
   - Add the SSH Key to Your GitHub Account in SSH keys page.
   - Test SSH connection: ssh -T git@github.com


