<template>
    <el-dropdown @command="handleCommand">
        <span class="flex-center">
            <el-icon>
                <User />
            </el-icon>
            <el-icon>
                <arrow-down />
            </el-icon>
        </span>
        <template #dropdown>
            <el-dropdown-item style="background-color: #eeeeee">
                Sign in as {{}}
            </el-dropdown-item>
            <el-dropdown-item >
            </el-dropdown-item>
            
        </template>
    </el-dropdown>

</template>

<script setup lang="ts">
import { useStore } from '../store';

const store = useStore()

const handleCommand = (command: string) => {


}

</script>

<style scoped>

</style>